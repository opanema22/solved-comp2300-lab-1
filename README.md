Download Link: https://assignmentchef.com/product/solved-comp2300-lab-1
<br>
In this week’s lab you will:

<ol>

 <li>get your discoboard and connect it to the computer</li>

 <li>create your first program using the VSCode IDE</li>

 <li>compile, run and debug your first program</li>

 <li>pledge to be a person of integrity in this course</li>

</ol>

<h2 id="introduction">Introduction</h2>

Welcome to the COMP2300 labs! These labs are the heart of the course, and they’re your opportunity to practice the core concepts you’ll need for the assessments. They are also your chance to explore and ask questions. If you don’t understand all of what’s going on in this lab, that’s ok—for two reasons:

<ol>

 <li>this is just the first lab (and it’s in week 1, not week 2 which is the case for some other courses), so we’ll cover all this stuff in detail in both lectures and future labs</li>

 <li>there are <strong>no dumb questions</strong> in this course, so the lab sessions are the time to speak up</li>

</ol>

The labs for this course have a few different recurring parts, and they will be presented using different coloured boxes:

<p class="info-box">General notes &amp; information will be highlighted in a blue box.

<p class="think-box">Sometimes you need to <strong>think</strong> about stuff before you go ahead. If you see something in a pink box (because your brain is pink—<a class="acton-tabs-link-processed" href="http://brainathlete.com/color-brain/">sortof</a>), that’s your clue to pause and <em>think</em>—how do you expect the next part will work? Take a moment to think before you blaze away and start coding, because then you can check whether you really understand what’s going on or whether you’re just copy-pasting stuff without really understanding it. If you <em>don’t</em> understand it perfectly, that’s ok—ask your lab neighbour, or your lab’s Teams chat (or your tutor directly) to help you understand.

<p class="push-box">All assignment &amp; lab submissions in this course happen through <a class="acton-tabs-link-processed" href="https://gitlab.cecs.anu.edu.au/comp2300/2021/">GitLab</a>. None of your lab work contributes to your final grade, however you are expected to push your lab work up to the server at various stages during your lab so that the tutors can see your progress and give you feedback. When it’s time to <strong>push</strong> something, it’ll be clearly marked in an orange-coloured box. Don’t just read past this box to the next section, where the “answer” might be discussed—make sure you attempt to complete the exercise yourself.

<p class="extension-box">Computer organisation and program execution (hey, that’s the name of this course!) are <em>huge</em> topics, and mastering them takes a lifetime. So the material in these lab sessions will only cover the fundamentals. However, sometimes there are interesting <strong>extension</strong> exercises you might try if you want to go deeper, and these will be in a purple box. If you don’t know how to approach the problems in the purple boxes, that’s ok too—you’ll do just fine in the course if you can do all the rest of the stuff in the labs. Still, it’s a chance to ask your lab mates and tutors and stretch yourself if you have time.

These coloured boxes will be used consistently through the lab material, so take a moment to familiarise yourself with what the different colours <em>mean</em>, or at least remember that you can come back here and check at any time.

<h2 id="exercise-0-setting-up-the-comp2300-software-environment">Exercise 0: setting up the COMP2300 software environment</h2>

Setting things up deserves <a class="acton-tabs-link-processed" href="https://cs.anu.edu.au/courses/comp2300/resources/software-setup/">it’s own page</a>. Go have a look, see you back here when you’re done &#x1f642;

<h2 id="getting-your-discoboard">Exercise 1: getting your discoboard</h2>

<p class="info-box">If you’re online, we’ll let you know how you can get your own discoboard in the week 1 lectures. For now you’ll be using the “discoboard emulator”, which is a piece of software that works in the exact same (well, sort of) way as a physical board–how to use it is explained a bit later in the lab. If this is you, <strong>skip to <a class="acton-tabs-link-processed" href="https://cs.anu.edu.au/courses/comp2300/labs/01-intro/#first-program">exercise 3</a></strong>.

If you’re in-person, during this lab the tutors will come around and give you a discoboard and USB cable of your very own—this is <strong>yours to keep forever</strong>. How exciting! The only caveat is that if you unenroll from the course <strong>before</strong> the census date (March 31) you have to give it back.

When you get your board, the tutor will also take note of the serial number (down the bottom on the “back” side of the board).

<img decoding="async" alt="Discoboard upside-down" data-recalc-dims="1" data-src="https://i0.wp.com/cs.anu.edu.au/courses/comp2300/assets/labs/lab-1/board-upside-down.jpg?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/cs.anu.edu.au/courses/comp2300/assets/labs/lab-1/board-upside-down.jpg?w=980&amp;ssl=1" alt="Discoboard upside-down" data-recalc-dims="1">

 </noscript>

<p class="talk-box">Handing all the boards out might take a bit of time, though, so thanks for your patience. While you’re waiting, push your chair away from the desk, turn, and say hello to the person next to you. Introduce yourself. Find out what degree they’re taking, and why they’re taking this course—is it a prerequisite or an elective? If you’re feeling extra-personable, ask what they like to do in their spare time. (If they’re already your friend, find someone else who you don’t know and talk to them instead.)

<h2 id="connecting-the-board">Exercise 2: connecting the board to the computer</h2>

<img decoding="async" alt="Boxed discoboard" data-recalc-dims="1" data-src="https://i0.wp.com/cs.anu.edu.au/courses/comp2300/assets/labs/lab-1/boxed-discoboard.jpg?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/cs.anu.edu.au/courses/comp2300/assets/labs/lab-1/boxed-discoboard.jpg?w=980&amp;ssl=1" alt="Boxed discoboard" data-recalc-dims="1">

 </noscript>

The discoboard connects to the lab computer (or your personal laptop) via a <a class="acton-tabs-link-processed" href="https://en.wikipedia.org/wiki/USB#Mini_and_micro_connectors">mini-USB</a> cable.

As far as electronics go, this board isn’t <em>super</em> fragile, but you’ll still need to be careful with it when you’re handling it and carting it around. That’s why you got it in a plastic container—keep it and your cable together in there. If you’re not used to handling electronics, here are a few tips:

<img decoding="async" alt="Holding your discoboard" data-recalc-dims="1" data-src="https://i0.wp.com/cs.anu.edu.au/courses/comp2300/assets/labs/lab-1/holding-discoboard.jpg?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/cs.anu.edu.au/courses/comp2300/assets/labs/lab-1/holding-discoboard.jpg?w=980&amp;ssl=1" alt="Holding your discoboard" data-recalc-dims="1">

 </noscript>

<ul>

 <li>handle it by the edges (as in the photo)</li>

 <li>don’t touch any of the pins or little microchips on the board</li>

 <li>keep the plastic case to carry the board around</li>

 <li>be careful of static electricity—if you’re the sort of person who regularly shocks themselves, then you need to ground yourself before touching the board</li>

 <li>the USB cable you received will only fit in <strong>one</strong> end of the board (even though there’s a different USB connector on the other end) so if it’s not going in, try the other end—don’t try to force it!</li>

</ul>

Once you’ve received your new discoboard, plug it in to the lab computer—the full-size USB end goes into the lab computer, and the mini end of the USB cable goes into the connector on the discoboard (up the “top” end, closer to the LCD screen).

<h2 id="first-program">Exercise 3: your first discoboard program</h2>

<p class="talk-box">With your lab neighbour, open up the main <a class="acton-tabs-link-processed" href="https://code.visualstudio.com/docs/editor/extension-gallery">VSCode documentation website</a>. Discuss with them: what makes a good documentation website?

Now that you’ve connected your board to the computer it’s time to turn everything on and see if it works. This exercise is a bit longer, so it’s broken down into stages: clone, edit, build &amp; run.

<h3 id="fork--clone">Fork &amp; clone</h3>

In this course, you’ll be using git a lot, and you’ll have a lot of git repositories (<em>repos</em> for short). Don’t fear: <a class="acton-tabs-link-processed" href="https://cs.anu.edu.au/courses/comp2300/resources/faq/#am-i-expected-to-know-how-to-use-git">you’ve done this before</a> (in COMP1100, one of the pre-requisites for this course) and it’s the same process here. Since we’re at the start of the course, here’s a tip: it’s probably a good idea to make a <code>comp2300</code> (or <code>comp6300</code>) directory somewhere on your computer where you can keep <em>all</em> of your stuff for this course.

Ok, now here goes:

<ol>

 <li>fork the <a class="acton-tabs-link-processed" href="https://gitlab.cecs.anu.edu.au/comp2300/2021/comp2300-2021-lab-1">lab 1 template</a> to your user account (i.e. <code>uXXXXXXX</code>)</li>

 <li>clone it to your local machine</li>

</ol>

You can do the “git clone” step in the terminal, or your favourite git client, it doesn’t matter. If you like, you can use VSCode’s built-in git support: here’s a link to the <a class="acton-tabs-link-processed" href="https://code.visualstudio.com/docs/editor/versioncontrol#_cloning-a-repository">general docs on this view</a>, and here’s the <a class="acton-tabs-link-processed" href="https://code.visualstudio.com/docs/editor/versioncontrol#_cloning-a-repository">specific instructions on how to clone a repo</a>.

<p class="info-box">Remember, this is all stuff you learned in COMP1100. We’ll make sure we help you out if you’re a bit rusty, but make sure you can fork, clone and (at the end) push to GitLab—<a class="acton-tabs-link-processed" href="https://cs.anu.edu.au/courses/comp2300/resources/faq/#can-i-submit-my-assignments-some-other-way">you won’t be able to submit the assessment items any other way</a>.

After you’ve cloned, open the top-level folder in VSCode. If you used the integrated VSCode git clone command, this will happen automatically. If you cloned the repo some other way, you’ll need to open the folder yourself with <code>File: Open...</code> in the command palette. Once you’ve done that you should see something like this:

<img decoding="async" alt="VSCode after opening the cloned repo" data-recalc-dims="1" data-src="https://i0.wp.com/cs.anu.edu.au/courses/comp2300/assets/labs/lab-1/VSCode-open-workspace.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/cs.anu.edu.au/courses/comp2300/assets/labs/lab-1/VSCode-open-workspace.png?w=980&amp;ssl=1" alt="VSCode after opening the cloned repo" data-recalc-dims="1">

 </noscript>

Again, the VSCode docs have a <a class="acton-tabs-link-processed" href="https://code.visualstudio.com/docs/getstarted/userinterface#_command-palette">good explanation of the user interface</a>.

Now, in the <strong>Explorer</strong> view, open the <code>src/main.S</code> file, you should see something like this:

<img decoding="async" alt="The main.s file in VSCodium" data-recalc-dims="1" data-src="https://i0.wp.com/cs.anu.edu.au/courses/comp2300/assets/labs/lab-1/VSCode-main-S.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/cs.anu.edu.au/courses/comp2300/assets/labs/lab-1/VSCode-main-S.png?w=980&amp;ssl=1" alt="The main.s file in VSCodium" data-recalc-dims="1">

 </noscript>

<p class="think-box">Even if you’ve never seen any assembly language before, what do you think this program does?

<h3 id="edit">Edit</h3>

Add some code so that <code>main.S</code> looks like this:

<pre><code class="language-ARM hljs"><span class="hljs-symbol">.syntax</span> unified<span class="hljs-symbol">.global</span> main<span class="hljs-symbol">.type</span> main, %<span class="hljs-meta">function</span><span class="hljs-symbol">main:</span>  <span class="hljs-keyword">mov </span><span class="hljs-built_in">r1</span>, <span class="hljs-number">0</span><span class="hljs-symbol">loop:</span>  <span class="hljs-keyword">add </span><span class="hljs-built_in">r1</span>, <span class="hljs-number">1</span>  <span class="hljs-keyword">b </span>loop</code></pre>

Save the file when you’re done. Don’t worry if you don’t understand all the details at this stage—the goal for this week’s lab is just to plug things in, turn them on, and make sure that everything’s working. If you have any problems, let your tutor know now.

<h3 id="build">Build</h3>

You can build (or compile—they mean the same thing in this context) your program using the <strong>Build</strong> command (<code>COMP2300: Build</code> in the <a class="acton-tabs-link-processed" href="https://code.visualstudio.com/docs/getstarted/userinterface#_command-palette">command palette</a>). You’ll see some stuff printed to the <a class="acton-tabs-link-processed" href="https://code.visualstudio.com/docs/editor/integrated-terminal">terminal</a> (near the bottom of your VSCodium window), and when it’s done it should look <em>something</em> like this:

<img decoding="async" alt="View after the build command" data-recalc-dims="1" data-src="https://i0.wp.com/cs.anu.edu.au/courses/comp2300/assets/labs/lab-1/VSCode-after-build-command.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/cs.anu.edu.au/courses/comp2300/assets/labs/lab-1/VSCode-after-build-command.png?w=980&amp;ssl=1" alt="View after the build command" data-recalc-dims="1">

 </noscript>

<p class="extension-box">The compilation process takes all the code (text files), <strong>translates</strong> them into binary instructions for the target <em>Instruction Set Architecture</em> (ISA)— ARMv7 in this case—and <strong>links</strong> them together into a binary file (<em>image</em>). You can learn more about it <a class="acton-tabs-link-processed" href="https://www.programcreek.com/2011/02/how-compiler-works/">here</a> if you want to read ahead, but you’ll also get familiar with it throughout this course.

<h3 id="upload">Upload</h3>

<p class="info-box">If you’re a remote student without a discoboard, <a class="acton-tabs-link-processed" href="https://cs.anu.edu.au/courses/comp2300/labs/01-intro/#run-debug">skip to the next step</a> &#x1f642; You’ll learn how to get programs onto the emulator there.

You’ve built the program <strong>on your laptop/desktop</strong>. To run it <strong>on your discoboard</strong> you need to upload it with the <strong>Upload</strong> (<code>COMP2300: Upload</code>) command. Again, afterward it should look something like this:

<p class="warn-box">The first time you flash a Discoboard you might see a <code>Error: init mode failed (unable to connect to target)</code>, this is solved by following the instructions in the “COMP2300: first time flash” command (<a class="acton-tabs-link-processed" href="https://cs.anu.edu.au/courses/comp2300/resources/software-setup/#flash-failure">link to troubleshooting here</a>).

<img decoding="async" alt="View after the upload command" data-recalc-dims="1" data-src="https://i0.wp.com/cs.anu.edu.au/courses/comp2300/assets/labs/lab-1/VSCode-after-upload-command.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/cs.anu.edu.au/courses/comp2300/assets/labs/lab-1/VSCode-after-upload-command.png?w=980&amp;ssl=1" alt="View after the upload command" data-recalc-dims="1">

 </noscript>

If you get errors at this point, then they’ll be printed (probably in red) in the terminal. Try and figure out what’s going wrong yourself, also checkout the <a class="acton-tabs-link-processed" href="https://cs.anu.edu.au/courses/comp2300/resources/software-setup/#troubleshooting">troubleshoot section in software setup</a>

<h3 id="run-debug">Run &amp; Debug</h3>

When you upload your program to the discoboard, it starts running it automatically.

To <strong>debug</strong> the program (stepping it through, inspecting the CPU &amp; memory states), we’ll use VSCodium’s built-in <strong>debugger</strong>—an invaluable tool for making things work right when we’re writing programs for the discoboard. You may have used a debugger like this before, or you may not have—that’s ok! We’ll lead you through the basics in the labs over the next couple of weeks.

Open up the <a class="acton-tabs-link-processed" href="https://code.visualstudio.com/docs/editor/debugging"><strong>Debug</strong> view</a> and make sure “build &amp; debug” is selected (<strong>if you are a remote student wanting to use the emulator, select “build &amp; debug (emulator)”</strong>).

<img decoding="async" alt="Debug config selection box" data-recalc-dims="1" data-src="https://i0.wp.com/cs.anu.edu.au/courses/comp2300/assets/labs/lab-1/VSCode-select-debug-config.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/cs.anu.edu.au/courses/comp2300/assets/labs/lab-1/VSCode-select-debug-config.png?w=980&amp;ssl=1" alt="Debug config selection box" data-recalc-dims="1">

 </noscript>

Click the green play button to run your program, pausing (“breaking”) on entry.

<img decoding="async" alt="Debugging in progress" data-recalc-dims="1" data-src="https://i0.wp.com/cs.anu.edu.au/courses/comp2300/assets/labs/lab-1/VSCode-debugging-in-progress.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/cs.anu.edu.au/courses/comp2300/assets/labs/lab-1/VSCode-debugging-in-progress.png?w=980&amp;ssl=1" alt="Debugging in progress" data-recalc-dims="1">

 </noscript>

The highlighted yellow line of assembly code (shown in the above screenshot) represents where the program is “up” to (next instruction to execute). When you first start it running, the IDE creates a <a class="acton-tabs-link-processed" href="https://en.wikipedia.org/wiki/Breakpoint"><strong>breakpoint</strong></a> at the <code>main:</code> label in your program, so when your program reaches that line of code it stops and waits for further instructions (from you!).

At this point, you can <strong>step</strong> through the code one instruction at a time using the debug controls:

<img decoding="async" alt="Debugger controls" data-recalc-dims="1" data-src="https://i0.wp.com/cs.anu.edu.au/courses/comp2300/assets/labs/lab-1/VSCodium-debugger-arrows.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/cs.anu.edu.au/courses/comp2300/assets/labs/lab-1/VSCodium-debugger-arrows.png?w=980&amp;ssl=1" alt="Debugger controls" data-recalc-dims="1">

 </noscript>

<p class="talk-box">Discuss with your lab neighbour—what do all these debug control buttons do? Play around with them together—can you see what effect they’re having on the program executing on your discoboard? Are you <em>pumped</em>?

If you want your program to keep running (i.e. to “unpause” the program) just hit the green play button (although it’s called <em>continue</em> rather than <em>play</em> when you’re debugging, because it continues after you last paused the execution). Once it’s running, you can pause it again by hitting the pause button, and even stop it with the red stop button.

Once it’s stopped, you can restart the whole process again in a new debugging session by going back to the start of these instructions.

<p class="info-box">Sometimes the debuggers are a bit flaky, and get into some problems. You’ll get the hang of recognising when things have gone wrong &amp; how to fix them. Remember that it’s ok to use the stop or restart buttons to try and get things back on track, or (worst-comes-to-worst) unplug and re-plug your discoboard.

You can also examine the values of your registers in the <strong>REGISTERS</strong> viewlet under the Debug View (see the bottom left corner in the below screenshot):

<img decoding="async" alt="VSCodium debug view, showing registers (bottom left)" data-recalc-dims="1" data-src="https://i0.wp.com/cs.anu.edu.au/courses/comp2300/assets/labs/lab-1/VSCode-registers-view.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/cs.anu.edu.au/courses/comp2300/assets/labs/lab-1/VSCode-registers-view.png?w=980&amp;ssl=1" alt="VSCodium debug view, showing registers (bottom left)" data-recalc-dims="1">

 </noscript>

If you want to control exactly <em>where</em> the system pauses for debugging, you can set a new breakpoint by clicking in the left-hand “gutter” (or margin) of the code view in the IDE. You should see a little red dot appear:

<img decoding="async" alt="A breakpoint (indicated by the red dot)" data-recalc-dims="1" data-src="https://i0.wp.com/cs.anu.edu.au/courses/comp2300/assets/labs/lab-1/VSCodium-breakpoint.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/cs.anu.edu.au/courses/comp2300/assets/labs/lab-1/VSCodium-breakpoint.png?w=980&amp;ssl=1" alt="A breakpoint (indicated by the red dot)" data-recalc-dims="1">

 </noscript>

<p class="think-box">The program isn’t running on the lab computer on the desktop (well, unless you’re using the emulator… if you are then &#x2728;<em>imagine</em>&#x2728;!)—it’s running on your discoboard. What does that <em>mean</em>? What are the implications for the way you run &amp; debug your program?

<p class="push-box">Make sure you understand what’s going on! Of course this is the goal of this course, and you will get to learn more as you go. But just a warning before you embark on this journey: make sure you don’t get tripped up at the final over some of these fundamental concepts, like <em>many</em> journey men before you did. Remember that your tutor is there for you to grill them with questions. &#x1f609;

<span class="kksr-muted">Rate this product</span>

One of the great things about uni is that you don’t learn in isolation (no matter if you’re online, or on-campus we’re putting in the effort to make sure this is true!). These lab sessions, no matter how you take them, will give you plenty of chances to <strong>discuss</strong> things with other people in your lab group. If you see a green box, read it and talk about the prompt with someone in your group–if you’re in person you’ll need to remember to do this social distantly, and if you’re online your tutors will explain how to start a discussion in Teams.