# MADVA

Our motivation for creating MADVA (Master's in Applied Data science Virtual Advisor) was to help our fellow Applied Data Science students avoid obstacles and better prepare ourselves for the coming semester and achieve our career goals. This app would significantly reduce stress during registration periods and help students plan future courses based on their interests and other students' experiences. This app would also be helpful for students who have less flexible schedules due to jobs, being in a different time zone, etc. With MADVA, our goal is to ensure that current and future DSCI students make the best out of their educational journey at USC.

To view the MADVA app go to the following url:
https://chaimilee-madva-main-4gkmtw.streamlitapp.com/

The main.py is the source code for the MADVA app and the requirements are in the requirements.txt file.

##Framework

MADVA was built on Streamlit, a frontend framework for building web applications in Python. We also utilized libraries including BeautifulSoup, Pandas, and Numpy.

##Architecture and Components

The architecture of MADVA is broken into 4 major parts: DSCI/CSCI Courses, About You, Personalized Course Recommandation, Applied DSCI Community, with the Applied DSCI Community having 2 sub-sections: Reviews and Contacts. This structure is meant to guide you through the process by first allowing the user to see the courses. Then, we gather some information about the user to match them with similar students and recommendations later on. The idea is to find the courses that someone with similar interests, background and previous class schedules as the user have taken. In this way, students in these groups can connect with each other and learn what worked for them and create a general community in the Data Science Program. Note that the app will output ‘Not enough information available’ when there is not enough data to generate an output for a specific user. Our hope is that once there are many users of MADVA, the app will generate more and more accurate results.

##References

https://classes.usc.edu/term-20221/classes/
https://catalogue.usc.edu/preview_program.php?catoid=14&poid=17593&returnto=5199
https://viterbigradadmission.usc.edu/programs/masters/msprograms/data-science/ms-applied-data-science/

##Contributor

@tyleralc
