# Module 5 >>

# Review: Research

This reading contains the code used in the instructional videos from [**Research**](https://www.coursera.org/learn/python-crash-course/lecture/WWJe4/research)

## **Introduction**

This follow-along reading is organized to match the content in the video that follows. It contains the same code shown in the next video. These code blocks will provide you with the opportunity to see how the code is written, allow you to practice running it, and can be used as a reference to refer back to.

You can follow along in the reading as the instructor discusses the code or review the code after watching the video.
![image](https://github.com/user-attachments/assets/f99122b4-11f1-456e-8b27-fbcab760564a)
# Review: Planning

This reading contains the code used in the instructional videos from [**Planning**](https://www.coursera.org/learn/python-crash-course/lecture/nLamj/planning)

## **Introduction**

This follow-along reading is organized to match the content in the video that follows. It contains the same code shown in the next video. These code blocks will provide you with the opportunity to see how the code is written, allow you to practice running it, and can be used as a reference to refer back to.

You can follow along in the reading as the instructor discusses the code or review the code after watching the video.
![image](https://github.com/user-attachments/assets/554e0010-18bb-4218-9133-b2cacac15524)
# Review: Writing the Script

This reading contains the code used in the instructional videos from [**Writing the Script**](https://www.coursera.org/learn/python-crash-course/lecture/l5dZ7/writing-the-script).

## Introduction

This follow-along reading is organized to match the content in the video that follows. It contains the same code shown in the next video. These code blocks will provide you with the opportunity to see how the code is written, allow you to practice running it, and can be used as a reference to refer back to.

You can follow along in the reading as the instructor discusses the code or review the code after watching the video.
![image](https://github.com/user-attachments/assets/606b8f86-830d-4ab6-88b4-9848f8a6cf83)
## **Introduction**

This follow-along reading is organized to match the content in the video that follows. It contains the same code shown in the next video. These code blocks will provide you with the opportunity to see how the code is written, allow you to practice running it, and can be used as a reference to refer back to.

You can follow along in the reading as the instructor discusses the code or review the code after watching the video.
![image](https://github.com/user-attachments/assets/83be602d-bff0-4370-99f1-a367a2dacd1c)
# Putting It All Together
<a href="https://github.com/fabfabit/MyStuff_public/blob/master/files/ProjMarr_slides.pdf" class="image fit" ><img src="images/marr_pic.jpg" alt=""></a>
# Python in action

Well done! Everything that you’ve been learning and all your hard work have brought you to this point. You’ve learned how to write a Python script from the ground up to solve a complex problem. You’ve also practiced how to:

- Identify a problem statement.
- Research the tools needed to help solve the problem.
- Plan an approach or best strategy to figure out what needs to be done, how it’s done, and how to structure the code.
- Write a script to solve the problem.
- Run and check that the code works the way it should.

Let’s now take a look at an example of how you can apply this process in the real world. This reading will provide you with a real-life example and walk you through the application of each step in the process.

## **The problem and solution**

Imagine this scenario: Every month, you are handed a spreadsheet with hundreds of new hires. You are asked to create user accounts for all of them on a Linux server. The formatting on the spreadsheet looks like this:

**username,password,real_name**

**amanda,,Amanda Alonso**

**ian,,Ian Ortega**

**eugene,,Eugene Konya**

**[...]**

Notice that the password field is empty for all the records. This means you need to generate random passwords for each user and then create their accounts. You also want to write the passwords that you generate back to a new CSV file so that you can tell the new employees their passwords.

This task isn’t difficult, but it is time-intensive if you create passwords and accounts for the hundreds of new hires one by one. Your solution is to automate this task in Python.

## **The script**

To automate the task of creating passwords and accounts for all of these new hires, the script should do the following:

- Read a list of new hires from **users_in.csv**.
- Generate random 16-character passwords for each user.
- Create each user account.
- Write the spreadsheet back to **users_out.csv** with the new passwords.

### **Your tools**

To help organize all the data, create accounts for the new hires, and create passwords for each new user, you first need to import a few standard Python libraries.

**import csv**

This library helps read and write the CSV files.

**import secrets**

This helps generate random passwords for each user account.

**import subprocess**

This calls the **useradd** command, which creates and adds each user account.

**from pathlib import Path   # to locate the data files**

This library helps to locate the data files for each user account.

### **Getting started**

After importing the libraries that help you execute your script, you need to get the current working directory and find the subdirectory where the CSV files are stored. Use **cwd** for “current working directory” and identify the path of the Python directory as a string:
![image](https://github.com/user-attachments/assets/b47948d8-d8f3-4e7e-bf3a-cfdba7bb2c4e)
Next, you use a with statement and an as keyword. The with statement helps with resource management, and the as keyword creates an alias for the resource you want to call. Consider the following code:
![image](https://github.com/user-attachments/assets/2b7e95fd-46b3-47ef-a626-322fdfdece84)
The CSV library takes care of reading and parsing the input from the file.

Next, you can use a **DictReader** object so that each row in the file is read into a **dict()** with the field names and values, like this: {"**username**": "**amanda**", "**password**": "", "**real_name**": "**Amanda Alonso**"}.

The following code is an example of how you use the **DictReader**:
![image](https://github.com/user-attachments/assets/769a9d08-e59e-4fc1-841f-c86966ce3f4c)
The input for the script is now complete! Now you need to set up the output. You create a DictWriter and use the same field names from the input, like so:
![image](https://github.com/user-attachments/assets/293bbd47-7a60-478d-aa76-8e0bbc06af16)
Now, you create a for loop to run through each record from the input file.
![image](https://github.com/user-attachments/assets/f16b2c09-4d1b-45fe-8c40-1f3e3741b3ee)
After the for loop, you use the secrets library that you imported at the beginning of the script to generate a random password of eight hex bytes, which equals 16 characters in total. Then, run the /sbin/useradd command to create each user. The check=True parameter causes the script to exit with a CalledProcessError if the command fails for any reason.
![image](https://github.com/user-attachments/assets/86288ed9-b667-4175-9215-12715b8d9d42)
Finally, you write the records back to the output file, including the passwords. When you run the code, the new user accounts and their passwords are generated into a new CSV file.Finally, you write the records back to the output file, including the passwords. When you run the code, the new user accounts and their passwords are generated into a new CSV file.
![image](https://github.com/user-attachments/assets/fb43e090-22fa-4e93-8c4a-61386ab56e87)
After the script runs, the output CSV file should look something like this:
![image](https://github.com/user-attachments/assets/b13f33b6-3220-49fa-b26e-1e5c9d69a259)
And there you have it! You’ve just saved yourself countless hours of creating hundreds of new employee accounts and passwords by creating a short, simple script to do the work for you.

## **Key takeaways**

There are many real-world applications for using Python: creating programs, solving complex problems, simplifying and/or automating time-intensive tasks, and many more. But the process always remains the same—identifying a problem, coming up with a solution, determining the tools that help you achieve your solution, as well as the most significant part—writing the actual script! As you saw in this example, any time you have a repetitive task, think of using Python to automate that task. The programming skills you’ve learned can make the work you do in your IT job a lot faster and more efficient!
# Course Wrap-up
# Join the community

Congratulations on completing the **Crash Course on Python** course!

You learned the fundamentals of programming in Python, including how to write scripts to perform automated actions, equipping you to automate IT tasks and become a more efficient IT professional.

You're not alone on this learning journey. Learning is more rewarding when you're part of a supportive community. Here’s how you can connect with fellow learners in the Google Automation with Python Certificate:

**Join the Google Automation with Python Community**

- **Discuss course content:** Get answers to your questions, share insights, and dive deeper into the material with peers.
- **Expand your network:** Connect with fellow learners from around the globe, build relationships, and grow your professional circle.
- **Unlock career opportunities:** Explore career paths, share job leads, and gain advice from others in the field.

Ready to dive in? [Join your Community](https://www.coursera.support/s/group-invite?id=MEY5OFcwMDAwMDB3bWt0U0FB)

The community is here to support you every step of the way. *Participation in the community is optional and offered at no cost to you.*
# Course 1 glossary

To use the glossary for this course item, click the following link and select “Use Template.”

Link to glossary: [Course 1 glossary](https://docs.google.com/document/d/10y9OfCElWm66-T0PKqb6dcepsNg1QrLOhrVJpsBT5vE/template/preview)

OR

If you don’t have a Google account, you can download the glossary directly from the following attachment.
![image](https://github.com/user-attachments/assets/a08b4e08-4b3b-497c-a0d4-5291373f9754)
![image](https://github.com/user-attachments/assets/193c1b1b-c85c-431d-9a0a-9b6742bdb4b0)
![image](https://github.com/user-attachments/assets/07a7732d-6882-4659-a71e-9047abde7b03)
![image](https://github.com/user-attachments/assets/31ee3e47-8507-4984-8030-8acb920505e3)
# Finding Your Path and Perfect Role

As you begin your career, you’ll have to navigate your way to find the perfect role for you. While there is no one way to find your ideal role, there are some things to consider to help you better understand what direction you want to take. This reading will focus on a few of the options to consider as you start to search for a job.

## Generalist vs specialist

One category to consider when attempting to find your right path is whether you want to work as a generalist or a specialist. A **generalist** is knowledgeable about many topics and has various interests, while a **specialist** is an expert in a specific field.

Generalists have broad, multifaceted roles that allow entry-level employees to gain invaluable experience in many different areas related to the field. Alternatively, specialists are focused on a singular aspect of IT. The table below provides an overview of common generalist and specialist roles.

**Common Generalist Roles**

- IT Support Specialist II
- IT Consultant
- IT Manager

**Common Specialist Roles**

- Automation Engineer
- Python Developer
- Software Engineer
- Cloud Engineer

Please note that the word “specialist” is often used in job titles, even for roles that include generalist-like tasks. When reviewing a job listing, be sure to read the duties and responsibilities assigned to that role so that you have a clear understanding of what you will be doing if hired.

## Choose your work environment

Choosing what type of environment works best for you is just as important as the type of role you select. Different types of environments have their own cultures and practices. As an entry-level employee, you’ll come across two types of workplaces: **agency** or **in-house**. You can also choose to work for yourself in a freelance role or even start your own business.

### **Agency vs In-house teams**

In the IT field, there are special agencies that offer IT services and technical personnel to other businesses on a contracted basis. These agencies can support multiple small to medium companies and often operate independently from the businesses they serve. As an entry-level employee in an IT service agency, you can expect to provide services to several clients. Short-term assignments are also common in agency contracts. Agencies may or may not offer employee benefits to their contracted technical personnel.

Alternatively, large companies and enterprises are likely to have an “in-house” team of internal employees to handle their IT needs. Although it is costly to employ an internal IT department, larger businesses prefer to have full transparency with their IT team and full control over the privacy of their users and confidential information. As an entry-level employee in an in-house IT department, you can expect to work closely with an IT team that has a variety of technical skills. It is common to build strong relationships with your team members, as you support one another on long-term projects. Internal IT department employees often hold full-time permanent positions and receive employee benefits.

**Large vs Small Companies**

Having a general idea of what you’re looking for in a work environment will help you narrow down your job search and land opportunities that are a better fit for you. You may prefer to work onsite for a large company for the diverse social atmosphere and professional networking opportunities. Some large companies and enterprises offer onsite cafeterias, gyms, and childcare, in addition to comprehensive employee benefit packages and career path opportunities. Or, you may prefer to work for a smaller company where you can form closer working relationships with smaller teams. You may want to work for a company that offers flexible work schedules and options that allow you to work from home, in the office, or a hybrid between the two.

## Key takeaways

As you navigate your job search, think about what you want in a career. Establish the types of roles you want to start with and the type of company you want to work for. Over time, your experience will help you make better-informed decisions related to your career direction.
# Exploring Technical Careers

This Google Professional Certificate is part of a bigger project called [Grow with Google (GWG).](https://grow.google/)

GWG offers some other certifications that can help you grow even more and pursue advanced job opportunities.

The offered career certificates include:

**Google Data Analytics Professional Certificate**

Take your programming skills to the next level with the R language in the Google Data Analytics Professional Certificate, where you will learn:

- Data types and structures
- Using data to solve problems
- How to analyze data
- Data storytelling with visualizations
- Using R programming to supercharge your analysis

To learn more about this certification visit:

[Google Data Analytics Professional Certificate](https://www.coursera.org/professional-certificates/google-data-analytics?utm_source=google&utm_medium=institutions&utm_campaign=gwgsite&_ga=2.162463295.2090059014.1666639119-999957063.1665442478)

**Google Cloud Network Engineer Professional Certificate**

Expand your automation skills to managing virtual machines in the cloud. Take a look at the Cloud Network Engineer Professional Certificate, where you will prepare for the Google Cloud Professional Cloud Network Engineer certification exam and you can learn about:

- Cloud network engineering skills
- Implementing VPCs
- Hybrid connectivity
- Network services
- Security for established network architectures on Google Cloud

To learn more about this certification visit:

[Cloud Network Engineer Professional Certificate](https://www.coursera.org/professional-certificates/google-cloud-networking#courses)

You can also grow your career by taking any of these Google Cloud professional certifications:

- [Cloud Network Engineer Professional Certificate](https://www.coursera.org/professional-certificates/google-cloud-networking#courses)
- [Networking in Google Cloud Specialization](https://www.coursera.org/specializations/networking-google-cloud-platform)
- [Security in Google Cloud Specialization](https://www.coursera.org/specializations/security-google-cloud-platform)
- [Google Project Management: Professional Certificate](https://www.coursera.org/professional-certificates/google-project-management?utm_source=google&utm_medium=institutions&utm_campaign=gwgsite-gDigital-paidha-sem-bk-gen-exa-glp-br-null&_ga=2.188375912.1961931751.1662579108-93933645.1661442239&_gac=1.53335386.1662581105.Cj0KCQjwguGYBhDRARIsAHgRm4_ThGr6fU1Y69wQRJqSe4hRoAyagufS1Gxs5_2mKay1uQyK6qU_Hs4aAqT_EALw_wcB)
- [Google UX Design Professional Certificate](https://www.coursera.org/professional-certificates/google-ux-design?utm_source=google&utm_medium=institutions&utm_campaign=gwgsite-gDigital-paidha-sem-bk-gen-exa-glp-br-null&_ga=2.150176886.1961931751.1662579108-93933645.1661442239&_gac=1.83696996.1662579831.Cj0KCQjwguGYBhDRARIsAHgRm4_ThGr6fU1Y69wQRJqSe4hRoAyagufS1Gxs5_2mKay1uQyK6qU_Hs4aAqT_EALw_wcB#courses)

If you have not yet taken Google’s entry-level certificate for IT support, consider signing up for the:

**Google IT Support Certificate**

This program takes your IT foundations to the next level, teaching you how to program with Python and how to automate common system administration tasks using it.

Across 5 courses, you will learn:

- Technical support fundamentals
- Troubleshooting and customer care
- Computer networking
- Operating systems
- System administration
- Security

To learn more about this certification visit: [Google IT Support Professional Certificate](https://www.coursera.org/professional-certificates/google-it-support?utm_source=google&utm_medium=institutions&utm_campaign=gwgsite&_ga=2.262561167.2090059014.1666639119-999957063.1665442478)
# Diversity and Inclusion

In the simplest terms, diversity means something that is different from the norm. Diversity in the workplace represents how organizations and their employees connect, engage, and respect people across all types of differences. More companies are beginning to emphasize their Diversity, Equity, and Inclusion (DEI) metrics as a way to stand out from their competitors. Companies with good DEI metrics tend to have higher employee retention rates, more satisfied employees, and increased innovation.

Diversity starts at the very top with a company’s executive leadership. Examine the leadership at the company you want to work for. The people working at the executive level is typically a good indicator of how diverse and well-represented their employees are as well. If a company’s executive leadership does not embrace diversity, the employees will experience greater difficulties in creating and maintaining that culture. Some questions to ask yourself as you are conducting research on companies:

- Does the company share their progress openly?
- Do they provide education and training opportunities to learn more about DEI and how people in the workplace are impacted?

There are several ways to assess whether or not a company practices diversity and inclusion. Here are a few resources to explore and gain better insights on the company:

- The company’s website. Assess their core values, history, mission statement, and keywords. See if their website includes any photographs of their employees.
- Their social media page(s). What kind of pictures and content do they post publicly? Check for photos of their employees, community outings, whether or not they recognize or celebrate various events or historical moments such as pride month, black history month, or world mental health day as a couple examples.
- Interview former employees. Conduct informational interviews to learn more about a company in general and ensure that workplace culture will be a good fit for you.

## Unconscious/Implicit Bias

Unconscious or implicit bias refers to the attitudes, stereotypes, judgements, or prejudices that we have unconsciously in our brain. This bias makes our reactions, thinking, and predisposition to information, actions, or environments alter in a particular way, whether it be positive or negative, without self awareness of its occurrence. It occurs beyond our control and could impact our decisions, actions, and understanding.

Unconscious bias is present, to some degree, in every single person and is developed from an early age through the course of one's life. Unconscious bias is associated with many characteristics such as race, ethnicity, gender, religion, sexual orientation, socioeconomic background, and educational background. Some of the common types of unconscious bias are:

- Affinity bias, which refers to preferences when choosing people to connect with. These people share similar interests, experiences, and backgrounds to your own.
- Attribution bias, which refers to the ways you perceive your actions in comparison to others. This bias is mostly in association with how you perceive success and failure.
- Ageism, which refers to negative feelings or discriminations against someone based on their age.
- Beauty bias, which refers to relating a person's physical appearance to their success, competence, and/or qualifications.
- Gender bias, which refers to a preference for one gender over others.
- Ableism bias, which refers to perceiving able-bodied people as the norm and people with disabilities should strive to perform at the same level as able bodied people without necessary accommodations. (examples: reserving a meeting space that is not wheelchair accessible, assuming people have to have a visible disability to be considered disabled, framing disability as something tragic or as an inspiration)

In order to identify our own biases, it’s important to know what are some of the causes of unconscious/implicit bias. Bias occurs because, as human beings, we are susceptible to tendencies and are creatures of habit. For example: humans tend to seek patterns, our brains are known to simplify the world, we get influenced by culture and/or media.

The truth is that no matter what the causes are, we are susceptible to implicit bias, and this could affect our relationships at work, the way we behave on certain occasions, the decisions we make, and how we react in our work environment.

The first step that we can take to remediate this behavior is to recognize that we are susceptible to bias and to identify it. The next step is to take actions that reduce the implicit bias at work. Some corrective measures that can be taken are:

- Increasing education. Educating employers and employees about the different types of unconscious bias and how to recognize it is one of the most effective methods to reduce this bias at work.
- Creating an inclusive work environment. Having an inclusive work environment will help to broaden perspectives and balance any prejudices.
- Taking into account the types of bias when making decisions. Check your decision for any cultural, racial, ability, or gender stereotypes.

## Key Takeaways

- We are all human, each with our own thoughts and opinions. It is important to recognize we do not all think the same way.
- Unconscious/Implicit Bias is an unavoidable result of being human and can influence daily decisions in our personal and professional lives.
- Make sure to be conscientious about unconscious/implicit bias when in the workplace by being open minded.
- A culture of diversity, equity and inclusion starts with executive leadership in any organization.
- Continuous education and training is very important and effective for reducing bias at work and promoting a culture of diversity, equity, and inclusion.
# Creating a Career Development Plan

There are several components and aspects of your potential career to consider while you are job searching. Before embarking on your journey, it is important to outline your career path. Doing so will help you find opportunities that align with your values, interests, and aspirations. As a Python automation developer, you have a myriad of options available to you. Many industries are hiring IT professionals to assist with Python development, debugging code, troubleshooting issues, recommending solutions, and automating processes on cloud platforms and in Linux environments.

## Identifying career goals

**What do you want to accomplish as a Python automation professional?** There are multiple specialist fields in the IT industry that will give you the opportunity to further develop and hone your skills in automating with Python. However, you can just as easily take the generalist route and cross-apply your knowledge of Python, cloud computing, and Linux to various roles.

**Do you aspire to eventually work in management in any capacity?** If so, it’s important during your job hunt to ask about opportunities for advancement or transition throughout the company. Some companies are limited in opportunities due to long-term employee retention or other factors.

**What are your unique strengths and skills that you bring with you to a company?** Identifying your strengths, both soft and hard skills, will help you stand out from other applicants. There are a plethora of transferable skills that you can use to leverage your application. If you’re not sure where to start on identifying your unique strengths and identifying your transferable skills, there are lots of online resources and platforms to help you get an idea.

Skill stacking is becoming more appealing to hiring managers and companies within the field of technology. Skill stacking is when employees combine skills from different fields or industries to produce novel ideas, approaches, and systems. Soft skills are the most important skills to have if you’re considering any position in management or if you want to work in a team-based work environment. Having the skills to hold conversations, navigate conflict, and collaborate with others will highly benefit your career.

## Creating a timeline

A common question that is asked in interviews is, “where do you see yourself in 5-10 years?” Creating a timeline for you and your career is helpful in gaining insight into what career opportunities will work best for you moving forward. One helpful way to gain clarity into this is to break down your bigger career goals into smaller goals.

Approach your job search and career in IT with an open mind. Be flexible with deadlines, milestones, and your own personal timeline. Be receptive to potential job opportunities that you might not traditionally apply to or pursue. Adaptability and flexibility are two of the most coveted soft skills employers look for in their employees.

Lastly, hold yourself accountable for your own progress. Technology is always changing and staying informed of all the changes that pertain to your job or specialty will give you an advantage over other employees. Look at taking other certifications, take online courses, read books on the subject, attend conferences, continuously network with other professionals in your field, and/or complete passion projects in your free time. Taking extra measures to inform yourself about your field and attending events with other professionals will greatly increase your chances of success and career satisfaction.
# Transitioning to a new career

In this reading, we will cover some tips for making a successful career transition. Making a career transition is both scary and exciting! The good news is that you will bring all of your past experience and knowledge with you. The trick to making a seamless career transition is to lean on the skills you already have while highlighting your new skills. Below are some ways you can do that!

## **Think about your transferable skills**

In your current career, you have gained tons of skills and knowledge that will help you as you make your career transition into the IT field. Communication, problem solving, critical thinking, teamwork, and self directed learning are all skills that are important in IT. Think about ways you have used these skills in the past. How could you apply these same skills to a role as an Site Reliability Engineer or Systems Engineer?

## **Showcase your new skills**

It is important that you also highlight the new skills that you have gained. To do this, it is important that you make changes to your resume, cover letter, and social profiles like LinkedIn. We will walk you through how to create these for IT roles  in the next courses.

You should also showcase projects you have worked on. GitHub is a great place to store projects and code. You can even link to your GitHub projects or repository on your LinkedIn!

**Note:** GitHub has great resources on how to create projects [here](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/quickstart-for-projects) and how to store code [here](https://docs.github.com/en/migrations/importing-source-code/using-the-command-line-to-import-source-code/adding-locally-hosted-code-to-github).

## **Get to know more with networking**

Networking is a great way to learn more about job opportunities you are interested in, as well as the IT industry in general. Meet people in the job role you’re interested in. Connect with them on LinkedIn. Job shadowing, volunteering, and interning are also great ways to gain more experience and knowledge!

## **Resources for more information**

Here are some more resources on making a successful job transition.

- This [article](https://www.linkedin.com/pulse/how-create-linkedin-profile-optimized-job-searching-emily) has tons of information on optimizing your LinkedIn profile. There is even a section focused on job transitions!
- This [resource](https://www.hackertrail.com/talent/tips/7-tips-to-improve-your-github-to-land-a-job/) has lots of information on how to use GitHub as a job seeker.
# Getting Promoted

You may already have a technical job and are building your skills to advance your career. You may be considering asking for a promotion.

You know that you have the Python and automation tools to successfully advance your career. Now is the time to plan for what to do next, with special consideration as to which career path to pursue. Perhaps you're interested in using your Python skills for analyzing data or developing software. You might be considering using your automation knowledge to streamline the maintenance of a Linux network or cloud environment.

What are the growth opportunities in your organization? Do they support training? Is this a transitional job? Is this your dream job? All these questions must be taken into account when planning your next steps. After you answer those basic questions, you have to prepare and space your next steps accordingly. If you are planning to grow within your organization, there are a few considerations that you should evaluate to get to the place where you want to be.

The first thing to consider when planning for a promotion is performing beyond average at your current position. This means proving to your employer that you are not only capable of doing your actual job, but that you are capable of taking on bigger responsibilities. How do you achieve that?

- **Work on your development.** You should always do your best to excel in your job. You can stand out from the crowd by adding value to your contributions to the company. How are you improving efficiency, saving money, bringing in new revenue? To get a chance at that promotion, you need to be the employee that gives more every day, willing to take new responsibilities.
- **Show leadership and be a team player.** Showing that you are a team player and can take leadership roles will help you to get noticed by your employer. Strive to be a role model, gain your coworkers respect, and motivate your team members. In other words, display and build qualities that will make you a good leader.
- **Continue your education.** When developing your career path, consider and plan for future certifications and training. For example, if you are planning to get from Python coder to Data Analyst, plan to earn a new certificate, like the Google Data Analytics Certificate. Check for your company’s Data Analyst job requirements and improve your skills accordingly.
- **Maintain strong work ethics.** Always be punctual for work, have excellent customer service, meet your deadlines, excel at your job, be respectful, and collaborate with your coworkers.
- **Communicate with your boss, your coworkers, and your customers.** Good communication is a key characteristic to display in any type of job, but when you are looking for a promotion, you need to excel in the way you communicate. It is crucial to know how to communicate. It will help when planning for your career path and add some communication training to your skill development.

### **Key takeaways**

Planning for a promotion doesn't necessarily mean that you are going to get one. Sometimes you will need to ask for it, or change roles or organization in order to achieve it. However, to be ready and able to demonstrate your value as part of an organization, remember to:

- Work on your development.
- Show leadership and be a team player.
- Continue your education.
- Maintain strong work ethics.
- Communicate with your boss, your coworkers, and your customers.
