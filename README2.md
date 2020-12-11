# In Review: Second attempt

## How I expected the challenge to go.

I decided that my first task would be to review with my colleagues and understand what I was missing regarding my approach. I was able to develop a more targeted approach this time, and plan a lot more efficiently. I knew I would have to essentially break down and rebuild my structure to accomodate each stage individually, and re-order my jenkinsfile to suit the pipeline. In my previous attempt, I was focussed on building and testing each stage in the pipeline individually in order to tackle each problem as it was presented. This presented a majour issue as soon as my Jenkinsfile began to have trouble building, and ate up a lot of my time just attempting to resolve a simple syntax issue. This time, I would build as many scripts as I could before attempting an initial build, and make bugfixes the latter stage, as the priority was building the foundation and building from there. I was well prepared to not finish the final steps as the time was quite tight, but I was ready to tackle the challenge with good vigour after the helpful advice of my colleagues.

## Building structure and code

I tore down much of my initial structure, and took a lot of advice regarding the pipeline. This time, I would use the pipeline as a timeline for executing code using small bash scripts to execute larger playbooks and scripts down the timeline. This allowed me to tackle each section as dependencies and build orders. I didn't want to try to take on the stretch goals this time, so my focus was on attempting to execute enough code to attempt a SAST test early in the pipeline.

## What went well?

I was pleased with the general structure, and the new format of the jenkinsfile resulting in a much clearer build steps that allowed me to build in a modular fashion. I felt that I tackled a much larger portion of the project in a shorter time, and even though I wasn't able to get a fully successful build to run, I was much more pleased with my progress. I had set up most of the correct steps and the processes and scripts that jenkins would need to execute them, including linking to bash scripts that would execute various playbooks that I am pleased with the construction of, and confident that with some minor fixes, would execute well.


## What didn't go as planned?

Disappointingly, I was not able to get a sast test to run, but just in the last moment I did manage to finally get my Jenkinsfile syntax fixed and Jenkins ran through (albeit unsuccessfully) the file, which was majour progress over my last few iterations. Unfortunately, I was also not able to run nexus, as that was put to the bottom of my priority list while I prioritised attempting to run a successful SAST test. It was disappointing to see that the jenkins build was unsuccessful, but this was tempered simply by the code physically running in the end, which was my majour sticking point throughout the challenge.


## Possible improvements for future challenges.

This being the last challenge, I feel my biggest point for improvement is my jenkinsfile configurations. I am confident with much of the work around this, but the jenkins syntax, despite being of simple construction, often catches me out in the simplest of ways. The matter of missing out brackets, adding too many brackets, and misaligning spacing is troublesome, and the fix is always simple to someone else looking at my work, and is likely something that will just get easier with more time and practise. There will be plenty of opportunity for this in the future, so it is just something I will keep in mind moving forward.

# Screenshots in review.

