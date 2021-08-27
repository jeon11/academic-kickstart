---
title: WA COVID Exposure Notification Usability Study
summary: "Task-based usability and AB testing on two versions of the COVID alert system in iOS and Android"
tags:
# - highlights
- research
- usability-testing
- qualitative-interviews
- affinity-diagrams
- ABTesting
- quantitative-ux

date: "2021-03-31T00:00:00Z"


# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: ""
  focal_point: Smart
  preview_only: true

header:
  image: '/headers/wa-header.png'
  caption: ''

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
<style>
.introduction {
  column-count: 2;
}
</style>

<body style="font-family:Arial; font-size: 12pt">
<div class="introduction">
<b><h style="font-family:georgia">My Role:</h></b>
<br><small>UX researcher in a group of 4 graduate students </small><br><br>

<b><h style="font-family:georgia">Methods:</h></b>
<br><small>**Usability testing**, **AB testing**, qualitative interviews, affinity mapping </small><br><br>

<b><h style="font-family:georgia">Timeline: </h></b>
<br><small>Jan 2021 - March 2021 (~10 week graduate course project)</small><br><br>

<b><h style="font-family:georgia">Stakeholders:</h></b>
<br><small> Apple/Google program managers, WA DOH, UW professor and research unit, designers </small>
</div>
___


## <h style="font-family:georgia"> Background: What is WA Notify? </h>

**Washington Exposure Notifications (ENX, also known as WA Notify)** is a tool that works through smartphones to **alert users if they may have been exposed to COVID-19.** Using Bluetooth, it allows smartphones to exchange randomly generated codes **without revealing any personal information**. **As of August of 2021, there are more than 2.31 million users.**

- If another user you've been near in the last two weeks tested positive for COVID-19 and added his verification code, anyone who was in close contact will receive an exposure alert.

- _If you are an iPhone user, you might have easily encountered this through your settings menu._


## <h style="font-family:georgia"> Overview </h>
The usability study combined qualitative pre and post-task interview questions and quantitative post-task usability metrics, such as Likert scales and NPS ratings.

Because majority of interaction happens once receiving an alert or testing positive for COVID, the study involved hypothetical situations, where users engaged with mockups of the interface. Having WA Notify available in two different versions for each OS (iOS and Android), AB testing was used to assess the experiences for each.

Three specific areas were assessed in the study:

1. Onboarding and enabling the notification
2. Receiving an exposure alert (hypothetical)
3. Entering a verification code once tested positive (hypothetical)


## <h style="font-family:georgia"> Objectives </h>
- **Understand first reactions** to the app, DOH website's information page, exposure alert, and overall user experience.
- **Provide evidence-based suggestions to improve the interaction** (not about the specific UIs).
- **Identify the experience gaps** that could be present in the different OS since there has been a significant churn rate for Android users.


## <h style="font-family:georgia"> Impact </h>
- The project was spotlighted in our HCDE program's [website newsletter](https://www.hcde.washington.edu/news/hcde-students-work-with-wa-department-of-health-to-study-covid–19-exposure-notification-app).
- **Ensured research deliverables meet the stakeholders' expectations** by checking in weekly since the planning stage.
- **Provided prioritized list of recommendations** for the three areas of focus, and assessed the experience gaps between the OS to the stakeholders.


## <h style="font-family:georgia"> Research Questions </h>
> <p style="font-size: 16pt"><mark><em>"What are the first impressions of using WA Notify, and the overall experience?"<br><br>
<mark<em>"Are there any perceived differences between the iOS and Android, and the usefulness of the resources provided on the DOH website?"</em></mark><br><br>


## <h style="font-family:georgia"> Research Process </h>
{{< figure src="research-process.png" title=""  caption="" width=full >}}

___
<br>
## <h style="font-family:georgia"> Design of the Study </h>

{{< figure src="userflow.png" title="The team initially visually laid out the user flow for each OS. The overall steps were broken down into three parts: onboarding, receiving alerts, and entering the verification code for positive COVID test results." caption="User flow by OS" width=full >}}

### Tasks:

- The study was broken down into **3 major tasks:**
  - **Task A:** Finding the instructions, and enabling the notification
      - _Using a DOH resource link provided, enable WA Notify on your device_
  - **Task B:** Receiving an exposure alert, and deciding what actions to take next
      - _You received a text from the DOH that you may have been exposed. What do you do now?_
  - **Task C:** Receiving a text message for testing positive from COVID, and deciding what to do next
      - _You tested positive for COVID and received a text from DOH. What do you do now?_

<br>

- After each task:
  - a confidence score rating question was assessed.
  - probed for areas of confusion, recommendations, and how the experiences in the two flows differed if any.
- Each participant was tested with both versions of the WA Notify.
  - One entire flow of OS was presented before presenting the other.
    - For example, a participant first completed the iPhone version. Then, completed the Android flow.
  - **To avoid bias or familiarity of the OS and the phone type the participants use, the order was counterbalanced.**


### Target Audience:

- The target audience was broadly defined as anyone who resides in WA state who has an Android or iOS device. This included people of all backgrounds, education levels, and technology literacy.
  - **_The more people who enable and use WA Notify, the more effective the system is in tracing the COVID._**
- For screener,

### Demographics:

- A total of 11 participants were tested.
- Age range of 18-34.
- During the screener, participants' information, such as phone types, whether they had previously enabled the notification, and tested for COVID, were identified.

{{< figure src="demographics.png" title="We had even split between Android and iPhone users. For iPhone users, we see that all participants had previously enabled the notifications." caption="Breakdown by phone types" width=full >}}

### Data Analysis:
{{< figure src="data-analysis.png" title="The team then took the data to do affinity mapping to search for patterns and common themes. <br>Each participant was color-coded." caption="Data Analysis" width=full >}}

---
<br>
## <h style="font-family:georgia"> Research Findings </h>

**_For readability, I highlight findings from Task B only._** Please reach out for more information.

### Task B. Receiving an exposure alert, and deciding what to do next:

{{< figure src="task.png" title="Participants were shown the exposure alert, and asked what they would do next." caption="TaskB Prompt" width=small >}}

### Insight #1:

- After receiving the alert, participants' immediate reactions were to:
  - **Learn more about the details of the exposure.**
      - Seeing where, when, and who, and even a map that pinpoints the possible exposure.
      - _"I would be curious where I might have been exposed ... **like a map that pinpoints the exposure.** (P1)"_
      - _"I would be concerned. Where must have I gone? Who did I get in contact with? (P8)"_
  - **See resources on getting tested.**
      - _"I expected to see more directions on testing sites and resources. (P11)"_

### Insight #2:

- Both flows were perceived as similar: **"simple"** and **"straightforward."**
- **Android's landing screen was preferred** because it showed a summary and possible exposure data, whereas iPhone initially shows a heavy text upfront.
    - _"**[Android] makes it more clear about the exposure data** and what to do next. (P7)"_
- Experiences in both versions made sense to the participants. Most concerns were raised in the DOH's 'What to do Next' resource web page.
    - _"Good until the point of clicking the link to 'Learn More.' (P4)"_

{{< figure src="insight2.png" title="**Android (left) has a summary page vs. iPhone (right) shows a heavy text upfront.**" caption="TaskB Insight2" width=full >}}

### Insight #3:

- Once the participants reached the page, they were asked series of questions on the overall impression and finding specific information on what to do next within the DOH's website.

{{< figure src="insight3.png" title="Participants had to find information on what to do next on the DOH website." caption="TaskB Insight3" width=full >}}

#### Pros:

- Comprehensive of the information in the page

#### Cons:

- Difficult to find relevant information
- Contents seem useful, but **too generic** that **doesn't meet the expectations** of the users that just received the exposure alert would look for

#### Confidence Rating:

- At the end of the task, participants were asked, <br> **_"How confident do you feel on what to do next upon possible exposure?"_** (5 being most confident)
  - **Flow 1.** iPhone settings to the DOH Website: 3: **3.5**/5.0
  - **Flow 2.** Android App to the DOH Website: 3: **4.0**/5.0

- Confidence rating in the Android version scored highly possibly due to the **better summary page that was provided.** However, with our sample size, **the rating should be taken as a grain of salt** at the stage.

---
<br>
## <h style="font-family:georgia"> Recommendations </h>

Based on the feedbacks provided from the participants and insights, I came up with 3 recommendations:

1. **Prioritize more ACTIONABLE information**
    - Information, such as COVID symptoms, were considered common sense at this point
    - _"To me, it feels like it's common knowledge, such as symptoms (P1)"_
    - _"I expected to see more simplified summary. **It's 2021 and I already have context of COVID** (P11)"_
    - _"Guidelines seem informational. Nothing to act on. (P4)"_

2. **Make information about testing sites more available**
    - After seeing the exposure notification, most participants wanted and expected to immediately get tested, but had hard time finding the correct information
    - Show information about nearby clinics or how to get scheduled for a test
    - _"Does it have information on testing sites? I would like to know what steps to take next. (P9)"_

3. **Less text and more visuals**
    - A lot of word and information were provided upfront while participants were going under stress from the alert
    - Visuals or infographics can better direct them to relevant information
    - _"It feels really wordy and it's **too much all at once.** (P8)"_

---
<br>
## <h style="font-family:georgia"> Limitations & Challenges </h>
1. Due to the sample size, the usability metrics collected were not examined for any **statistical significance.**

2. **Recruiting was mainly convenience sampling:** More than half of the participants were affiliated with the University of Washington, which may not be fully representative of the general public of WA state.

3. The usability tasks were limited to remotely observing participants' interactions within the prototype as the tasks involved hypothetical situations, such as getting an exposure or positive test alert.

4. For the scope of the project, only limited DOH webpages were tested.


**Have any questions? Please reach out!**

<br>

[Back to top ^](#)
---
</body>
