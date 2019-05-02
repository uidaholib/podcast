---
title: Editing
nav: true
---

# <i style='color:black;' class='fas'>&#xf0c4;</i> Editing Audio
Now we'll walk you through the process of editing—cleaning up your audio, arranging it, and mixing it all together (i.e. fading talking bits in and out around music, breaks, etc.). 

{% capture text %}

If you haven't yet, go ahead and import your main audio (i.e. your voice recording, interview, etc.) into Audacity using the steps outlined in the <a href="{{ '/content/1-Recording.html' | relative_url }}"> previous section on recording audio</a>.

##### 1. Getting rid of unwanted room noise

When you originally recorded your audio, remember how we recommended that you capture a little bit of "silence" before you began speaking into the microphone? What that did was capture the ambient noise of the room/environment—the hum of the air conditioning, a busy street outside, a window fan, etc.—so that we can get a "noise profile" and get rid of it. Here's how:

**a.)** Using the ``Selection`` tool (looks like: ``I``), highlight a portion of that beginning noise, and in the top toolbar, go to ``Effect > Noise Reduction``

 {% include figure.html img="editing-1.png" alt="intro image here" caption="" width="100%" %}

**b.)** In the resulting pop-up window, under "Step 1," select ``Get Noise Profile``
- This will teach Audacity what the noise you want to get rid of "looks like," and thus the program will be able to easily find it everywhere in the recording. 

**c.)** Highlight the entire audio clip (double click anywhere in the audio clip with ``Selection tool``) and go back to ``Effect > Noise Reduction`` and experiment with the settings under "Step 2" (Noise Reduction, Sensitivity, Frequency Smoothing) until you find the best sound (using the ``Preview`` button)
- Notice that **too much** of the Noise Reduction effect will start to cut into parts of your speech, which you probably don't want—so keep experimenting until you find a happy medium. 

**d.)** When you find a setting you like, click "Ok" to officially apply the effect.
{% include figure.html img="editing-2.png" alt="intro image here" caption="" width="100%" %}
---
##### 2. Getting rid of unwanted speech and other sound

Everyone, um, when they talk, like, sometimes we use a lot of, sort of, filler words when we're thinking of what to say. Now is your chance to easily cut-out any unwanted speech patterns and other noises (like a bump in the mic, or long periods of silence during a monologue or interview, etc.). Here's how we do it:

**a.)** Using the ``Selection`` tool (along with the ``Zoom`` tool, which looks like: &#x1F50E;) highlight a portion of the audio clip you want to get rid of and...  
**b.)** ...hit the delete key.  

—***Done!***  

**But there are some important things to consider, here.**  

It's nice to be able to cut out vocal tics like "um" and "like," and it's especially nice to get rid of long pauses in order to keep the podcast moving swiftly along, but **cutting too much away can have some strange effects**—namely making the speech sound rushed and unnatural. You probably want *some* kind of human element, right?  

There may only be the above 2 steps to this process, but it's more involved than it seems, because you're going to want to listen to the entire audio clip and **assess your cuts based on the surrounding speech and context**. You do a lot of pausing, re-listening, deleting, re-re-listening, deciding that "uhhhhh" was actually kind of cute and personable, "undoing," etc., before moving on.

{% endcapture %}
{% include card.md text=text header="Cleaning up your audio" %}

---

{% capture text %}

Now that you have nice, clean, noise-free audio, we can start laying out the architecture of your podcast. You may, at some point, want to **split your audio clip into segments** that you can move around (i.e. for music breaks, or commentary, etc.). Here's how to do that:

**a.)** Using the ``Selection`` tool, click on the spot in the audio clip where you want to make the split (doing so should result in a thin, vertical, black line bisecting the clip).  
**b.)** In the top toolbar, go to ``Edit > Clip Boundaries > Split`` to make the cut.  

Now you have two separate clips. **Moving the audio around** is simple: from the top tool bar, select the ``Time Shift`` tool (looks like &#8596;), and drag the clip into the desired position.

{% endcapture %}
{% include card.md text=text header="Arranging your audio" %}


