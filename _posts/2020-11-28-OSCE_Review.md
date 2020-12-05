---
layout: post
title: OSCE (in 15 hours)
---
The purpose of this blog post is to serve as a reminder for myself of my experience in gaining OSCE. 

OSCE was always a long term personal goal of mine. When I heard it was being retired I immediately signed up, as I did not want to miss the opportunity to do the (in my head) legendary certification.


# Pre-Signup Prep
The only real prep I did before starting the course was [SLAE32](https://www.pentesteracademy.com/course?id=3). I was already fairly comfortable with x86 assembly, however, I felt it would be best to reinforce that knowledge.

Key things I did to make sure I got the most out of SLAE32:
- Watch the videos and take notes (for note taking I recommend [Notion](https://www.notion.so/)).
- Do the exam at the end, the assignments will make sure you understand assembly, at least enough for OSCE anyways.

# CTP Course
I personally didn't spend much time on the course. I mostly skimmed through the chapters and made notes on each of the main topics for further research.

A lot of the content was quite straight forward for me. It was just procedures that had to be followed to achieve the end goal. However, the key thing here is to make sure one had a full understanding of each step; what it is doing, why it is necessary and consider other ways to achieve the same result.

# Exam Prep
From the course content and reading various blogs on the exam, props to [h0mbre](https://h0mbre.github.io/) and [Jack Halon](https://jhalon.github.io/OSCE-Review/) for their writeups, I formulated the following study list:
- Alphanumeric shellcoding
- Egghunters
- SEH overwrites
- Hex Encoded Characters
- Jumping
- Partial overwrites
- 2-Stage payloads
- Socket reuse
- Fuzzing
- Backdooring PEs
- Bypassing AV

I used the above list as my learning objectives and spent the majority of my prep practicing with [vulnserver](https://github.com/stephenbradshaw/vulnserver).

# Exam
### 0500 - Zzz... Lets do this!
My OSCE exam began at 0500. This was far earlier than I initially wanted it to be but I figured it would be a long haul anyway, so the start time probably wouldn't matter too much across the overall exam time.

### 0515 - READ THE QUESTIONS (FULLY)
After fully reading and dissecting each of the tasks, I opted to focus on one of the 'easy' ones. This was something I hadn't quite done before but I was confident I knew how to do it.

### 0615 - Almost there but no dice
Hitting a temporary road block but happy with my progress thus far, I decided take a quick break and grab some coffee.

Breaks are important, they allow you some time think away from the screen and most importantly load up on caffiene.

### 0645 - +15 points
The first 'easy' fell and in good time too, I felt confident about time and moved swiftly onto the second easy task.  

### 1030 - Things aren't always as simple as the seem
The second 'easy' challenge looked straight forward initially. I followed my methodology but for some reason I couldn't quite complete the task.

### 1230 - Don't get stuck at a roadblock
After a few more hours of working on the second 'easy' task, I took a short break and decided to move on to the 'hard' tasks.

### 1400 - +30 points
With a bit of trial and error I had managed to complete one of the 'hard' tasks. The particular method I used in the end was interesting and not something I had actually encountered before.

### 1430 - Lunch break
Having 45/90 points in the first 9 hours I decided to take a short lunch break. 

### 1600 - +15 points
Having spent a few more hours wrestling with the second 'easy' challenge I finally managed to complete the task. It required some creative thinking but I felt a bit daft for not considering what I ended up doing earlier in the day.

### 1630 - Coffee break
With 60/90 points in the bag, I only had the last 'hard' task to complete. Given what was involved in this task I was extremely confident. Therefore, I decided to take another coffee break.

### 1730 - Access Violation
I quickly discovered the route I had to take with the last task, however, I decided to do my due diligence and performed further testing to see if there would be any other exploitable paths.

### 1800 - 'This is the way'
Opting to put my money on the original route, I began following my exploitation methodology. Fortunately, the difficult parts of this task I had actually come across before and therefore knew exactly what I needed to do.

### 2000 - +30 points
After just 15 hours the last task was completed, I had managed to obtain all available points (90/90) and just now had to focus on not making a mess of the report. I then used the second day to make sure I had all of the required screenshots, write and submit the exam report.

# Reflection
OSCE, in my opinion, was easy. It differed from OSCP in the sense that you were always told what to do, you just had to know how to do it. Because of this, I believe OSCE is all in the prep, if you had prepared enough then it would be a piece of cake, if you hadn't... well then you were in for a long 48 hours of wishing you had prepared more. 

All in all, I enjoyed the course and I am very proud to become an OSCE, albeit a legacy OSCE now! Thanks offsec for the course and exam.

[<img src="{{ site.baseurl }}/images/screenshot_osce.png"]({{ site.baseurl }}/)
