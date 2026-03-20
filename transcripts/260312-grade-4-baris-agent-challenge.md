# ⚪ 03-12 Workshop: Minecraft Education Coding Challenge — Agent Pathfinding, Timed Dual Plate Activation, Debugging, and Loops

**Color Code:** ⚪ Transcripts

> **📌 What This Is:** Clean Markdown transcript for classroom, lesson, or teaching use.
> **🧭 Start Here When:** You need the fuller transcript source behind the lesson notes.
> **👀 Best Use:** Skim the timestamps and speaker sections first, then pull out the teaching moves, lesson flow, or class-management details you need.

---

## ⚡ Quick Scan

- 📄 **Source TXT:** [03-12 Workshop_ Minecraft Education Coding Challenge — Agent Pathfinding, Timed Dual Plate Activation, Debugging, and Loops-transcript.txt](./260312-grade-4-baris-agent-challenge.txt)
- 🧩 **Transcript-derived lesson notes:** [Transcript-Derived-Source-Materials-Notes.md](../lessons/evidence/Evidence-Notes.md)
- 📍 **Transcript Type:** Teaching / lesson / classroom note

## 📝 Transcript

### 00:00:07 · Speaker 1
Music
### 00:00:30 · Speaker 2
Are you doing this?
### 00:00:34 · Speaker 3
I'm gonna lose it. How do you know? We can't play Minecraft. We're gonna play Minecraft on something. I didn't play with my old one. We're playing.
### 00:00:47 · Speaker 2
Minecraft on something.
### 00:01:02 · Speaker 4
We do not like the Minecraft thing again. But we are going to do like.
### 00:01:07 · Speaker 3
That specific lesson.
### 00:01:09 · Speaker 4
As I wait, we're gonna do some pointers to help everyone get on the side. What are you guys doing? Start a game?
### 00:01:26 · Speaker 3
I need to explain it because Enderman is going right now.
### 00:01:32 · Speaker 3
And somebody killed a guy. The Enderman stole his homework.
### 00:01:44 · Speaker 4
Try to open all and make sure that Minecraft is opening. Stop whatever you guys were doing before and make sure that Minecraft opens.
### 00:01:54 · Speaker 1
What is that?
### 00:01:56 · Speaker 4
So make sure you open it. You're still gonna do the five minutes you guys are doing. Just make sure that you're mic up. Let's listen. My hope is that today.
### 00:02:30 · Speaker 2
We're doing that. So my hope is that you guys are finished.
### 00:02:36 · Speaker 5
Finishing this. And then today you can move on into the rest of this series. There's one where you're saving turtles, and then there's one where you save polar bears after that. In order to finish this, I would say the majority of you are stuck here.
### 00:02:59 · Speaker 5
A couple of hints I want to give you. Number one, most of you haven't read the directions thoroughly, and that's why you're stuck.
### 00:03:08 · Speaker 4
You don't even know what you're trying to do. The directions for this tell you that you need to be standing on both gold plates at the same time. Can somebody who's come up walk this guy out to a gold plate? It'll take me a half an hour. Walk him out to a gold plate on that side. So listen, you need to be standing on.
### 00:03:29 · Speaker 5
One gold plate, the agent needs to be standing on the other gold plate. You only have twenty seconds to get that done. Once you hit the wait, what are you doing?
### 00:03:40 · Speaker 4
He needs to go there. I don't know. Just physically walk there. Just show them how to go there. We have to get out of here before he starts talking about. This is what he's talking about So
### 00:03:54 · Speaker 5
There is perfect. Thank you Charles. Here's the deal. It doesn't matter which one's which. You can get the agent to stand on this one, and you stand on that one, or vice versa. Let me tell you something. If you're fast enough to do the orange obstacle path in twenty seconds, then you can code the agent to get to that blue one no problem. Remember, your agent floats; he doesn't need to go through that whole thing; he could just.
### 00:04:28 · Speaker 5
Walk over and walk out. You can write complicated code to get him to follow that whole blue thing, or you could just get him to float over the top of the water and get to the plate. Number two, if you can't run out on that thing in twenty seconds because every time you hit the play button, the door here shatters. If you can't run out there quick enough, all you got to do is with your character, run out and start on this block. If you are standing on this block, and you run the code to get the agent to go to the orange gold plate, then you'll be good to go. You guys see what I mean? So then the agent will go to that gold plate, and you are already standing on this when you hit start. So it's like a cheat. So if you still can't do it after having those hints.
### 00:05:26 · Speaker 5
Mr. Garcia, I will come sit with you or Charles, or one of the other kids can come sit with you guys. This is supposed to just be a tutorial to get you started so that you can do the rest of the lessons in the series here. Anything you want to add?
### 00:05:42 · Speaker 4
That was perfect. Go ahead and get to work here. If you need us
### 00:05:49 · Speaker 5
Let's just give us a call. I'll make sure.
### 00:05:56 · Speaker 3
It's not letting me go. It's not letting you go away? Because I need to do it like 20 seconds. So I need that to go over there. Exactly. So how do I do it? Because I tried to do the um. That's what. Oh then what do I. I need help.
### 00:06:17 · Speaker 4
Just go back to where you're going. So I'll look at this now. Make sure you reset that thing.
### 00:06:27 · Speaker 4
One woman was saying right now is if you're not fast enough because you both have to get on the other side.
### 00:06:42 · Speaker 3
I'll be able to be fast enough.
### 00:06:43 · Speaker 4
You can start, go there and wait for your agent, then run your code, and then your agent can go there.
### 00:06:51 · Speaker 3
I will be fast enough.
### 00:06:55 · Speaker 4
So what you need to do is code so your agent goes there.
### 00:07:01 · Speaker 3
I did that last time. I think it was on.
### 00:07:03 · Speaker 4
Because you need to go there on the twenty-second.
### 00:07:08 · Speaker 3
So where do I go here? Or how do I call it?
### 00:07:13 · Speaker 4
You want to code it because
### 00:07:14 · Speaker 3
But do I need to look at what we're going to use?
### 00:07:18 · Speaker 4
So apparently, which I didn't know, you can have exactly. You can have your robot basically. You see where it is right now? See where it is right now? Sorry, I just thank you. You see where it is right now? You can make it go. Can you give me the view of the golden thing with the robot? There you go.
### 00:07:53 · Speaker 4
You can make it go this way, all the way here. You can count: one, two, three, four. And then you can make it go all the way straight to the golden. So one, two, three, four, five. And then you can go floating all the way to the golden. But you need to count how many steps. So right now, I mean how many steps forward because he's gonna go this way. So you want to make it turn, what is this? You're gonna make him turn right first. And then you're gonna make him go forward. How many steps? One, two, three, four because the whole thing is right there. One, two, three, four, five. No because he's already standing there so you don't count that one. So it's one, two, three and four then.
### 00:08:50 · Speaker 4
Let's test the logic first. Turn right, go forward four times.
### 00:08:56 · Speaker 3
You guys supposed to go one, two, three, four.
### 00:08:58 · Speaker 4
You can do it that way but I'm giving you the easiest code. Because if you do it that way, he still has to turn again, and then you have to go forward again.
### 00:09:07 · Speaker 3
So I will go.
### 00:09:10 · Speaker 4
We're gonna go over that together. Let's see it, and then we'll go over that together. So he turned right and then goes. Do it or not? Because we have more steps to count. That's why I want you to do it with me. So turn right? And go. Give me thirty seconds. One two three four, right? What? So turn right, four forward, right? And then you make it turn left, right? You want it to float, right? Now how many steps does it need for the golden one? That's what you need to count out. Exactly. So now hold on. Let's count this first. It's one two. Count with me.
### 00:09:50 · Speaker 4
Four five six. So now you need to go and continue counting to see how many right. So we have six so far. That's assuming that your bot can float. Ten. Is ten in total? So try it out. Let's see if it works. So we talk about turning right? And now what? No hold on. This is what we talk about turning right? Was it right? Here make sure. It's right. And then we talk about going forward. Right. What is it?
### 00:10:49 · Speaker 4
Then step right. But before going forward, we needed to go forward how many times? Was it four times? Three. Four times was it? We are assuming you're both close. I don't know if that's true. So before that we say it's gonna turn right? But it needs to turn left. Right, okay, what's left I think it was left, because it already turned right? Oh yeah, left. So now I'll go back first to get this first one. You might have to reset. Where's your robot? Where's your agent? Right there. There you go. So go all the way back so you can see him moving to see. To show.
### 00:11:38 · Speaker 3
Now I forgot he was something in the.
### 00:11:40 · Speaker 4
Was it T for terminal, right? And then one, just enter. Enter is easier. That's not the apparently you didn't change the name of your. You didn't change the name, hold on, exit. Change the name otherwise you're gonna have to type wrong and no one's okay? Right so T for terminal one enter see more space, one more or two I don't know, go count them, you go count them and take.
### 00:12:16 · Speaker 4
Alright.
### 00:12:46 · Speaker 4
Can you give me the view where I can see the golden block and the agent? Perfect. There you go. That's actually even better. That's perfect. So let's see the agent. You're seeing the agent over there, right? Since your agent can float, they just make it go. You don't think it's better if you just go that way and then go straight to the government blocks? Let's do that. To go that way, what turn is that? I would just go when you're going. No for your agent to turn. Then I'll just step. You don't do it like that. Remember he's under twenty seconds now we need to do your work.
### 00:13:46 · Speaker 4
You need to reset and add the steps that we're missing. So go reset, go to the beginning.
### 00:13:58 · Speaker 4
Bring the code back. The code that we had before, that we put together. Bring it back because you cannot code like this because you're gonna run out of time.
### 00:14:41 · Speaker 4
And then after you turn left, you wanna move forward four times. So you see what we're doing, remember? You remember why we're turning left? Because we want it to go straight and float. Four is good. You made it turn right. It's gonna go the opposite way. You want it to float. There you go. So here, this is what we're doing. Look. You can see his computer. Don't do that. You need to reset it. Look at his computer. So he's turning left. How many times? One, two, three. Four. So they wanted to float to the golden one.
### 00:15:38 · Speaker 4
And then after that, you want to turn left, you go forward. Then you want to turn. What direction? So he's facing this way right? So what direction is it? So that's his left and this is his right? So he's turning. Oh yeah, he has to turn right here. He has to turn right, go back. Because I think it's right. I said that! You're right. You were right. Sorry. And put it first because. So now you can go back, right? So he's turning right and he's going forward, right? And now you want to turn. Two times. Right? What is two times? Where to turn left later on when we can go forward?
### 00:16:37 · Speaker 4
So go. So now we're going to make a turn left. If you added to the step. Now go back. One more. How many steps are there? You cannot do it like that, Tony.
### 00:17:07 · Speaker 4
You did one extra. You cannot hold like that. Let's go back here. He's not listening. So you did the right? And you did four. Now you're doing left. Now he's facing this way, right? Now you need to count how many steps goes to the golden one. How many? Go count them. Yo! Yo! So you can count them from here. Look at it! Go to the agent side first. You can come in from here. This is a good spot where you are. Mr. Garcia, look at that one. How many is this? One? There you go. You said it's three. You can't do it because right, you run out of time. You have to use the entire code so when you run to A again, it takes there on the 20 seconds and we go there on the 20 seconds. So I'll give that like four times. So here. So, let's count this, how many steps right? Can you count with me? The one.
### 00:18:12 · Speaker 3
And this? Six, nine.
### 00:18:22 · Speaker 4
You repeated that one. One, two, three, four, five, six, seven. You need more steps. Seven? Now we need the other steps to go to the other side and continue counting. How many more steps are here? Eight, nine, ten, eleven, twelve. Right? Was it twelve that you used? I think we counted twelve. Right? You can always reset and try again. Forward and twelve. Look what he's doing? Oh, you already got him there. So now you need to go there. You need to be there on the golden plate. I do. There you go.
### 00:19:07 · Speaker 4
Try running it. And make sure the. Should I go back? No. Try running it now so you can see it. You need to do T, terminal T and then one. Terminal T. And then one. Enter. Presently.
### 00:20:06 · Speaker 4
Enter. Go, hurry up. Hurry up. Where am I? Try reset it. You didn't even reset it. How to level? You said try again thing? You ran out of time. You need to be faster. You had the code already. Just reset it. Run it again and try to get there on the 20 seconds. Do what he's doing. Go to the middle. You see where he is in the middle? Bring yeah, he needs to come back. Reset it. You need to do it on the twenty seconds. Finish? I'm gonna take a look at it. Let's look at it go.
### 00:21:05 · Speaker 4
So you wanna just make a float there? Mr. Ramos said you can make a float there. If you want to make a float, just turn right. Go forward four times. See how one two three no one two three and four. That will give you a straight direction to the golden block. But it's gonna be a lot of code. Are you okay with that? So you need to go forward one, two, three. Let's see how many children. We're going off. You need to go forward. Put it forward again. Oh yeah!
### 00:22:04 · Speaker 4
See how many times? One, two. And now you need to make a turn this direction, and then you need to go one, two and three. Agent turn.
### 00:23:00 · Speaker 4
This is the last time I tell you that group over there. Don't do this again. Last time. Do I need to repeat myself? I'm not picking anybody, I'm not saying you did this or you did that. I'm saying this is the second time that I hear something that happened in there. And it's the last time that I'm gonna tell you to stop it, whatever it is. I don't care.
### 00:23:28 · Speaker 4
So one more right. How do you move? Here. You go there forward and you turn right. Now you wanna move forward. One, two and three. Move forward. Take one forward. Make sure those are three. We counted three.
### 00:23:59 · Speaker 4
So you went three times there, and then you shift, and then three times there. You need to quote all of that. So now you have how many steps do you have in here? One and two, right? No, because that one is off. Why did I have to jump in? No, because we're doing. I don't know! Jumping with it! Oh no! This is a zombie! One. Two. You would be here. You're gonna be here. And then count that as that one. And then you have to go up. Yeah. But you're gonna have to turn. So you're gonna have to turn left. Right? And then a two right here. So if you can get out to that orange block, it's gonna be something similar. You're gonna have to turn left, right? I mean do exactly so now remember that thing is higher, right? So keep the.
### 00:24:57 · Speaker 4
One is fine, but then you want to move forward again, one right. And then you're going to end up here, that's where you are. Then you're going to end up, so you're going to have to move up again and forward. So we're going to have to move repeat this again, one up again and one forward again. You want to try that? No. You have one more step to go up. Just bring another up. This one here.
### 00:25:46 · Speaker 3
All the way down and then. I'm helping. Ouch! And then forward again. You're right here. You're right here, right now. You're right here
### 00:26:00 · Speaker 4
Right now. And now you need to turn left. You're right here with the code. That means you turn left and then you how many? One, two, three, four? One two three, right? Okay so you turn left and then you go forward three times. Come in. So now you're here, right? You're here. So now you turn, you need to turn right. And then you need to go down. Turn right? You turn right and then one step over and then one step down. Right? Yep. And then one step forward.
### 00:26:54 · Speaker 4
And one step down. There you go. It's just long. Make sure it's down, okay? Make sure it's down low. There you go. You're almost there. So now you're down, you're here. Forward, down. Forward, downward again. Almost there.
### 00:27:23 · Speaker 3
So do we need to go forward and down?
### 00:27:25 · Speaker 4
Try down. Forward and down. Both of them are down? Yep, because it's two times that you go forward and down. I think so you're good. You already did that one down. So now if we go here, we do forward, down. Forward, down. Now count how many steps you got forward? Right here? Yeah, three because you're already there. Left no, you keep going forward. With that three, all the way down. Take this one. So you count to three, put it right there. You need to turn right. You go here, and you need to turn right. How many steps here? Running. It's alright. This is so.
### 00:28:22 · Speaker 4
You counted them already? I can't do it anymore. I'll just keep going forward right now. There you go. And if I do T1? Then now is it one? Is it one? You're done. He said one is main man one is two point seven five seconds. Now, if you're holding and your body is gonna be okay. But the thing is that hold on, reset it. The thing is that you're in the middle right? Where are you? You're gonna have to run when you press T and then one, you do T right? And then one and then enter. It's gonna get there before you. So if I were you I would go to the middle then press T.
### 00:29:18 · Speaker 4
What in the middle right there? What do you wear on top right there? On top? It's pull. Execute right now, do t and then one just do the same thing enter. It's gonna go there. Your body's gonna go there. Go! You need to go. You need to be there under 25 seconds. Oh my god. Oh shit! You're gonna have to reset it and do it again. Try it again. Reset it again? Try again! I've reset it right here since we said. Your code is set. You need to reset. Reset. Because your body's already. Your agent knows how to get there already. You have to figure out how to get there under 25 seconds. And I told you how to do it, just stay in the middle reset.
### 00:30:15 · Speaker 4
First go to the middle and then reset it when you're ready. You want to try jumping? Wow, awesome. Nice, you guys okay perfect. Did you figure it out? Did you figure it out already?
### 00:31:13 · Speaker 4
He said the game. Did you make it? Did you make it on the twenty second?
### 00:31:20 · Speaker 3
He helped me with skill. Where did I go? I tried to move but right here.
### 00:31:35 · Speaker 4
So what about this door? What about this door over here?
### 00:31:44 · Speaker 4
So let me ask somebody here. And this. It's the same thing, but it should work. Where's your agent? All the way down there. Because I told you have to be in the middle. You're cheating. I can't get back there? You can't. You can reset it, right? Can I be a player? You can be in the middle and reset it from there. Can I press T1, enter? Did you reset already? There's a reset right on the bottom. Right here. Press it right now? How many times? The moment you press it, it starts counting. Oh! Yes. That's why you're losing.
### 00:32:42 · Speaker 4
I only one. One. You want to reset it again and try it? Just reset it again. There you go. Now do see? Yeah?
### 00:32:53 · Speaker 3
My agents are coming!
### 00:32:59 · Speaker 4
It's it's a problem. Go reset from the beginning. Can I help you now? I'm going to help you now. Press C for code. I just press and then just.
### 00:33:39 · Speaker 4
Is one over there? How many steps do you have to go there? You can't tell me. This doesn't tell you, I'll say. Just try counting the blocks because you can kind of see the blocks in here. One, two, three, four. It's a little bit weird why. I'm here. You wanna try doing twenty to get there? Do you have a timer? You don't have a timer, right? So just try it. So the reset is not working? There you go. Now I ended again maybe. Is he already starting the timer? No, you can't. You can't reset it there.
### 00:34:36 · Speaker 4
It's fine. It's fine. See. One enter. Let's go. You should be there. No? Oh wait, wait for your code. Oh you have two wrongs? You have to come on now, maybe one All right? Let's reset it again. now it's reset Now. Let me see one. Alright. I think it's. Go. Oh! Can you show me? You can do it. You can do it. It's just. You don't have to rush because we have a lot of time. It seems like you are rushing unnecessarily. Go there again and reset it and don't rush, take your time. Just go the middle again, alright? Go the middle again, alright? Stay there.
### 00:35:36 · Speaker 4
Stay there. Let's look at your agent. Let's look at your agent to make sure that to know that he's moving. Reset. Only one, that's it. Now there's three. One, take your time? Don't rush, take your time go There you go, that's it should open now You need to stand there with the. You guys got it.
### 00:36:35 · Speaker 4
Super advanced in this stuff. Look at that, people are just finishing the water stuff. Only the water?
### 00:36:46 · Speaker 3
Lesson one? Wait, they're still finishing like lesson one. Hey
### 00:36:54 · Speaker 4
That's come on. Let's stop and clap about that guys.
### 00:37:04 · Speaker 4
I'm not gonna talk to you guys. You wait for a while. How do I get this? Teach me. How do I get this? Oh go there. You need to go there. Your agent can float but you can't. Guys, keep it down. You guys are smart but keep it down. My screen is backwards. Move the agent along the turtle track by using an agent move forward block. Go the gate. Turn on, press the play button. It will compile the code. You have to move forward here. How many steps do you need to move forward to the gate? Did he go the gate? Where is the gate? This one, right? There's trail. There you are.
### 00:38:03 · Speaker 4
How come you guys are not giving him pointers? You guys are so far. So move your eight from there to here. How many steps did you use for this? Twelve, fourteen, five, fourteen. I would change the run to one, just so you don't have to type run all the time. Here. Wait, yeah. Now do T for terminal and then do one. You're not. It works if you do H2O. I know, but if you do T, you're gonna start learning something that you're gonna use later. You see that terminal right? You use it for programming.
### 00:39:01 · Speaker 4
So you want to start getting comfortable with that. Give him pointers. Make sure to give him pointers. What is it? I'm in there. You're fine.
### 00:39:20 · Speaker 3
Where'd you guys find this thing? They're all like in the shelters. There's no one in there like random stuff. What are you here? Stuff a bunch of random stuff inside the shell.
### 00:39:37 · Speaker 4
You got it? You got her? Now did she help you? Does she want you to float? That's what I'm doing. You can do it multiple ways. The way you did it was right. The same issue is, The same issue that you have before is the timing. So it doesn't matter. I think it opened, there's hope for you already. Did it?
### 00:40:07 · Speaker 3
No. It's not open? Go over there. Alright so let's do this. Guys, keep it down, come on man!
### 00:40:25 · Speaker 4
There is an easier way to do this.
### 00:40:31 · Speaker 4
No singing guys here. This is not a music class. I just drowned it.
### 00:40:42 · Speaker 3
Shut up. Why can't you see so young? You should be quiet.
### 00:40:54 · Speaker 4
So let's do it. Let's do it the easiest way, Let's just go there, right?
### 00:41:01 · Speaker 4
Turn right, go forward four times. You're turning right here, go forward four times and you'll end up here. Then just go straight there. I think it's like twelve. Then turn left.
### 00:41:33 · Speaker 3
[ 0 m 0 s 125 ms-0 m 2 s 345 ms][ unintelligible][.
### 00:41:41 · Speaker 4
0 m 2 s 345 ms-0 m 6 s 8, 75 ms][ unintelligible][ 0 m 6 s 8, 75 ms-0 m 9 s 195 ms] Can you get that?[ 0 m 9 s 195 ms-0 m 12 s 475 ms] What's it gonna be?[ 0 m 12 s 475 ms-0 m 13 l 683 ls] You get that, Right?[.][.][.], In twenty like.
### 00:42:02 · Speaker 3
So did it already start the second?
### 00:42:04 · Speaker 4
I just gave you an example. Let me reset it. There you go. You go back now. My is there? It's fine, the code is there, the code is on it. Go there and reset it.
### 00:42:30 · Speaker 4
How you guys doing? How you doing? Let me see. Show me. Not the first one.
### 00:42:50 · Speaker 2
I'm on the water.
### 00:42:54 · Speaker 4
Do you want to give us some pointers here so we can finish this fast?
### 00:43:06 · Speaker 4
I'm gonna help him too with the water. I think no.
### 00:43:09 · Speaker 3
He got stuck. I think that happened. You're not supposed to try again but I was already there.
### 00:43:19 · Speaker 4
What happened is that when you're here, let him get there first and then you go. You did it? He still didn't.
### 00:43:28 · Speaker 3
I'll let you try getting out of there.
### 00:43:32 · Speaker 4
So do you, I think you need to be there first. Then try that. Now try reset from here. Let's try that. Go to the middle again and try reset it. Do you want me to help you or not? I can help you because this is gonna take you a lot of code man. So what do I do now? Now reset it from here. Can you take a look? Everybody. So run your robot. Let's do three, two, one. Okay go there and get first. Go get first before your robot gets there. Where is it? There. Is he drowned? Alright. I'm gonna need you to drive because I don't know how to drive this.
### 00:44:26 · Speaker 4
I just throw. I don't care. Did I say I care before when I said, I told you guys, I didn't care? That I didn't care what happened or who was at fault. So you're gonna go over there and you're gonna sit over there. Please take your computer here. Buddy! You good? You have a chair over there? There you go. If I hear another weird sound, somebody else is gonna get out of this table. He's gonna help you. Come here. Go. Actually, you're too smart for this class. You need to help her. He's gonna help you. That's his job to help you because of what he let happen. Go here again. It's okay, but you let that happen. You know what they were doing and you let it happen. So here, help her. That's your job.
### 00:45:24 · Speaker 4
That's your time. Can you do that for me? And then I'm gonna edit the slide. Help her please. Hold on, let me help somebody that is behind. Run? You want me to give you pointers?
### 00:45:46 · Speaker 3
Like that, then I turn.
### 00:45:48 · Speaker 4
You have to do this under 20 seconds. You're never gonna make it like this. Do you want me to help you? 20 seconds? On the 20 seconds.
### 00:45:56 · Speaker 3
It gets it says it. Where's the 20 seconds?
### 00:46:00 · Speaker 4
You'll see in the command. And then command so if you reset it here, you reset it. Reset and you reset it. He'll tell you in the command. Do you want me to give you some pointers? Yeah! This is what most of your classmates are doing. You can make your agent float. You can just turn this way. Turn. This way go forward and then you can turn that way and go forward. Oh! And how many steps do you have to go to the golden one? Count that with me.
### 00:46:43 · Speaker 3
One Two Three Four.
### 00:46:47 · Speaker 4
So you have to turn right. Go forward. How many steps? Four, and then you need to turn. Look at my hand. You need to turn left. And how many steps do you need to go the golden one? I counted them already. I can tell you. You can go and count them yourself. I like kick it on there. You want to count them? Twelve. Go the golden one.
### 00:47:21 · Speaker 4
What's the other side? What's the other side that you're trying to go?
### 00:47:25 · Speaker 3
Don't want to. I don't know.
### 00:47:36 · Speaker 4
What does your agent need to go? Let me see your card first. I don't want it to be like earlier time because the questions are important. That's probably not a good thing. I mean. She must have. I'm fine either way. You made it go forward. Four times. Can you reset this again? But I think it was from the whole beginning. For the whole beginning? That's different from the other one. Where is your agent somewhere here? One here? Where do you need it to go? You want it to come down?
### 00:48:17 · Speaker 4
I don't know what to do. You don't know where it needs to go? Is that what you're saying? And then just text me and let me know. Let's read instructions here. It says, use the agent to destroy the tree that is in the way by using agent destroy. Okay, where is the agent destroy? So you need to use that. All right. Agent collect all four. Great! Agent collect all four. There you go.
### 00:48:48 · Speaker 4
So you have that. And then try using a repeat, which is this one. To make the code more efficient. When done, press the play button to compile. So now, you need to check where to have your alien to destroy this green stuff. Where is it? Is it in the center? let me see if there's green stuff here. Destroy the three trunk. Which one is the three trunk? Is this one? So you need to bring your agent down, right and make it destroy that with the command that I gave. Are you having that? Did you help her? Thank you.
### 00:49:49 · Speaker 3
I went through here, but then I went down here. It just brought me back there.
### 00:49:56 · Speaker 4
So did you read the instructions? Because I think it wants you to do something. It says here: Use the agent to destroy the tree trunk that is in their way by using agent, destroy and agent collect. All right? Is it that tree? This tree? Like this one? What is the tree trunk? It's a tree trunk. This is it. Is it not working?
### 00:50:25 · Speaker 3
I need help. Come on, wait. This is it. Oh boy, this one's a lot of work to get out of here. I think you're right. Destroy tree trunk! I think it's stuck.
### 00:50:36 · Speaker 4
So first let's figure out what the tree trunk is.
### 00:50:39 · Speaker 3
It's this, it's all of this, and it goes up all the way up there because I need to go through there. That is a trunk?
### 00:50:47 · Speaker 4
I think three trunk is the wood stuff in there.
### 00:50:54 · Speaker 3
There's wood right there. How do I get to destroy it?
### 00:50:59 · Speaker 4
So let's read here. It's using the agent destroy. See here? Let's put that here first. Let's put what you need in here. Let's put it in here first so we don't know what you're doing. We don't know what we're doing. Agent collect, agent destroy and then what does it say here? Agent collect.
### 00:51:16 · Speaker 4
I. So what we're going to do now is we're going to figure out what no before you run it, let's figure out what you actually need to do here. Where's your. So I don't maybe this what you need to destroy, right? So let's just. Maybe this cause, cause it's on the way. Let's destroy. Let's destroy it. It's already facing there, right? So what we're going to do is, we're gonna totally.
### 00:52:11 · Speaker 4
Agents in a loop, right? Let's try it four times. I'm sure you need it more times just to try it. Let's tell this Troy and move forward, right? And then we'll take agents collect all, right? And then let's put this in here. Let's change this to one. Right? There you go! It's working! See. It's working. You know what's the problem? What? Go to the code. Let's see what's the problem. Your code here. What do you think is the problem? There you go, you got it, but wait before you do that no, you're moving forward. Yes. Again, how many before you do that you need to have one of these because remember you made a mistake, so you need to make it move forward. So he finds some more right no, you don't want in the loop you want it.
### 00:53:08 · Speaker 4
Outside of the loop, because you're gonna mess up the loop. You want it outside of the loop. There you go, yep. Now what? Come on. You're good man. Wait no, I see. You don't need me. You know what I mean? What you need to do is make sure that you have more. Is that what he wants? How do I know I have more? You count them. How many did you do right now? And now you shoot again. Did it stop freezing? Perfect. So let's see here. Where are you right now? Let's make it go all the way forward. I think it's like. Remember? Eleven nine. Let's make it move forward as many times as we can. Let's use another one on this side.
### 00:54:07 · Speaker 4
Eleven is that right? Put eleven in there. And then two three. There's a run? Line up, she gotta line up.
### 00:54:26 · Speaker 3
Put your chair in, boy! Perfect, now let's go this way. Yes ma'am! Out of here you go, baby!
### 00:54:35 · Speaker 4
There you go! You need to make it come all the way here. Alright. That, you need to go forward one, two, three. And then you need to go. Then you need to turn left. One, two, three. And then right. One, two, three. You needed a look. I'm gonna put your for next time. You want this.
### 00:55:07 · Speaker 4
You did a good job.
### 00:55:38 · Speaker 4
I don't want to talk today.
### 00:55:40 · Speaker 3
But we got a meeting right now, so I have to be at the. Here's a cat. There's a cat. What's that thing?
### 00:55:52 · Speaker 4
Do you know how quiet he got the moment I forced him to go through it?
### 00:56:02 · Speaker 2
We're gonna need.
### 00:56:04 · Speaker 3
We're gonna need four minutes and again five minutes. It's not obvious that if you see both of us have to see.
### 00:56:14 · Speaker 4
Sounds good, five minutes and then call you and then five minutes and then call her, sounds good.
### 00:56:42 · Speaker 4
Oh yeah, let's go.
