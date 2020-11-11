# Maker Challenge: Augmented Reality Programming Challenge
<p>In this maker challenge, students will use Unity and Microsoft Visual Studio to explore augmented reality(AR) programs. Using the engineering design process, students will modify, enhance, and redesign one of the AR programs to meet a real-world need. Throughout this process, students will gain valuable coding skills by using the C# coding language to implement their changes. The following is a walkthrough that will provide students within an introduction to the engineering design process, show them how to navigate the AR demos, and provide resources for coding with C#. This walkthrough will also provide notes on good coding practices and project expectations.</p>

<h2>What is the Engineering Design Process?</h2>
<p>The engineering design process is a process engineering teams use to solve problems. There are several steps involved, and the steps are <b>iterative</b>, meaning that steps are repated as many times as needed. The steps of the engineering design process are: ask, research, imagine, plan, create, test, and improve. You can learn more about the engineering design process <a href="https://www.teachengineering.org/design/designprocess">here</a>.</p>

<img src="https://www.teachengineering.org/Images/edpHub/EDPHub_Graphic.png" alt="The engineering design process" width="50%">

<h2>Materials, Download & Installation</h2>
<p><b>NOTE: This project is only compatible with Windows operating systems</b></p>
<p>To begin working on this project, you will need a computer to access certain software. You will also need an <a href="http://shop.orbbec3d.com/Astra-Pro_p_35.html">Orbbec Astra Pro Camera</a>. The following intructions provide a step by step walkthrough on the download/installation process for the software you'll be using.</p>

<h3>Microsoft Visual Studio 2017(or later)</h3>
<p>This is where you will build your code. Micrsoft Visual Studio 2017(or later) is available <a href="https://visualstudio.microsoft.com/free-developer-offers/">here</a>. Once there, click the relevant download according to your operating system. For example, if you have a Windows computer, download Visual Studio Community for Windows. You can access more detailed download instructions <a href="https://docs.microsoft.com/en-us/visualstudio/install/install-visual-studio?view=vs-2019">here</a>.</p>


<h3>Download Unity v. 2018.2.9(or later)</h3>
<p>Unity is where we will build our demos. It has the ability to create screens and a variety of other useful features. You can download Unity <a href="https://store.unity.com/#plans-individual">here</a>. On the 'Individual' tab, you can select the student or personal plan. For the purposes of this walkthrough, we'll select the 'Personal' plan.</p>
<img src="https://user-images.githubusercontent.com/39998983/96674168-c2f19380-132d-11eb-8676-c42474ce884d.png" alt="Unity installation landing page" width="60%">

<p>Next, select the 'Start Here' button.</p>
<img src="https://user-images.githubusercontent.com/39998983/96674599-c5082200-132e-11eb-9a42-00bf61260917.png" alt="Unity installation page" width="60%">

<p>Lastly, select the "Agree and Download" button. This will start the download and walk you through the setup process for your particular device.</p>
<img src="https://user-images.githubusercontent.com/39998983/96674627-d6512e80-132e-11eb-8b38-cab5d00c7ef3.png" alt="Unity terms page" width="60%">

<h3>AR Physiology Demo Downloads</h3>
<p>Now it's time to choose the demo you would like to work on. There are three main AR Physiology demos to choose from. The <a href="https://github.com/MASILab/AR_Mirror_Muscle_Demo_Clean">Muscle Demo</a>, the <a href="https://github.com/MASILab/AR_Mirror_Bone_Demo_Clean">Bone Demo</a>, and the <a href="https://github.com/MASILab/AR_Mirror_Replay_Demo_Clean">Replay Demo</a>. The muscle demo will allow you to view different muscles within the body, the bone demo will allow you to view different bones within the body, and the replay demo allows you to automatically record and replay your renders. You can explore each demo and begin thinking about what demo you'd like to work on. For example, here's a preview of what the bone demo looks like:</p>
<img src="https://user-images.githubusercontent.com/39998983/96675662-026daf00-1331-11eb-9612-c037a10bf0e7.png" alt="AR Bone demo preview" width="60%">

<p>To download a demo via GitHub, click on one of the demo links. Here they are again:</p>
<ul>
  <li><a href="https://github.com/MASILab/AR_Mirror_Muscle_Demo_Clean">Muscle Demo</a></li>
  <li><a href="https://github.com/MASILab/AR_Mirror_Bone_Demo_Clean">Bone Demo</a></li>
  <li><a href="https://github.com/MASILab/AR_Mirror_Replay_Demo_Clean">Replay Demo</a></li>
</ul>
  
<p>Once you're at one of the Github pages, select the "Code" dropdown, then "Download ZIP." Open the file and unzip it once it's downloaded.</p>
<img src="https://user-images.githubusercontent.com/39998983/96676747-b112ef00-1333-11eb-82cc-0b8b38a90cf1.png" alt="Github download walkthrough" width="80%">

<h3>Orbbec Camera Driver</h3>
<p>Lastly, once you have your <a href="http://shop.orbbec3d.com/Astra-Pro_p_35.html">Orbbec Astra Pro Camera</a>, you'll need to install the Orbbec Camera Driver. You can download the driver <a href="https://orbbec3d.com/develop/">here</a>.</p>

<h2>Warm Up: Exploring the Demos</h2>
<p>Now that you've got your software downloaded and your camera plugged in, you're ready to explore the demos! To open a demo in Unity, start by launching Unity on your computer. Launching Unity should open a Window that looks like the image below. Go ahead and select "Open."</p>
<img src="https://user-images.githubusercontent.com/39998983/96723925-cd834b80-1374-11eb-9b24-b45f20d2f84b.PNG" alt="Open project in Unity" width="80%">

<p>Next, we'll select the demo we'd like to work with. </p>


<h3>The Bone Demo</h3>
<p>We will explore the bone demo first!<p/>

<h4>Getting started</h4>
<p>Make sure you have the <a href="https://github.com/MASILab/AR_Mirror_Bone_Demo_Clean">AR Bone Demo</a> file downloaded. Open this demo by selecting its file.<p/>
<img src="https://user-images.githubusercontent.com/39998983/96725391-72eaef00-1376-11eb-9cc6-c813a2e648f6.PNG" alt="File explorer window" width="80%">

<p>Your screen will look similar to the screen below. To see the demo in action, navigate to the 'Assets' folder towards the bottom left. Within the 'Assets' folder, navigate into the 'Scenes' folder.</p>
<img src="https://user-images.githubusercontent.com/39998983/96729646-fe667f00-137a-11eb-9ad0-8bb66fe3f9db.PNG" alt="File explorer window in Unity" width="80%">

<p>Now, double click on the "BoneDemo" to open it.</p>
<img src="https://user-images.githubusercontent.com/39998983/96730080-746ae600-137b-11eb-8fd3-98e041ae5820.PNG" alt="File explorer window in Unity" width="80%">

<p>Navigate over to the "Game" tab and select the play button to start the game! You'll be able to see the bone-overlay on your screen in real time! Try to get the bones from your head to your feet showing by moving so that your whole body is in view. As you move, make observations about what you see.</p>
<img src="https://user-images.githubusercontent.com/39998983/96731249-a92b6d00-137c-11eb-9988-55055cccc037.PNG" alt="Playing bone demo" width="80%">

<h4>Diving Into the Code</h4>
<p>Let's take a look at the code for this demo and try adding another bone overlay. Start by opening the "SkeletonViewer." You'll see that a panel opens to the right where you can view what bone images are linked to specific joints.</p>
<img src="https://user-images.githubusercontent.com/39998983/96733226-d2e59380-137e-11eb-9f04-d95f26c25b51.PNG" alt="Playing bone demo" width="80%">
<p>The Orbbec camera recognizes each of the following labeled joints.</p>
<img src="https://user-images.githubusercontent.com/39998983/96734009-b3029f80-137f-11eb-8dd7-6127334e41a1.png" alt="Playing bone demo" width="40%">
<p>Look in the bottom left panel where you accessed the "Assets" folder. Inside the "Assets" folder, navigate to the "Prefabs" folder, then the "3D_BODY_Bones" folder. Here you can view and add 3D bone overlay images, we'll use one of these images shortly.</p>
<img src="https://user-images.githubusercontent.com/39998983/96742994-1fce6780-1389-11eb-903f-47533f1f7f1a.PNG" alt="Playing bone demo" width="80%">

<p>To the right of the screen, SkeletonViewer should still be open. Right click on the window and select "Edit Script" from the dropdown menu. This will open up Visual Studio.
<img src="https://user-images.githubusercontent.com/39998983/96744453-ab94c380-138a-11eb-96ed-7b41fde3d949.png" alt="Edit script" width="80%">
 
<h5>Coding in Visual Studio</h5>
<p>Now that we've accessed the code, follow these steps to make some changes!</p>
<ol>
<li><p>First, skim through the code and make some observations. Notice that there are a lot of lines of code highlighted in green that begin with two forward slashes, these are called <b>inline comments</b>. Inline comments are comments that are written by programmers to make code easy for other humans to understand. These comments don't affect how the code runs. Inline comments are not only helpful for other people who may view the code, but also helpful for the programmer to remember how and why they did things.<br><br><b>Press Ctrl + F to use the finder tool and search for the comment "Bone Prefabs"</b></p></li>

<li><p>Next, we are going to add a GameObject. In computer science, an object is basically a value in memory referenced by an identifier. You can learn more about objects <a href="https://www.khanacademy.org/computing/computer-programming/programming/objects/pt/intro-to-objects">here</a>. We are going to create a GameObject to add a bone between hand joints. Add the following code after the existing GameObjects:</p><p><code>public GameObject Prefab_LeftHand_RightHand;</code>
</p>
</li>
<img src="https://user-images.githubusercontent.com/39998983/96749209-23b1b800-1390-11eb-90b0-17c8aae01217.PNG" alt="Search in finder" width="80%">
<li><p><b>Press Ctrl + F again and look up the comment "Instantiate bone gameobjects"</b> we are now going to define a new bone. This will allow us to pair a bone image with bone joints in Unity. To do this, scroll down a little to add the following code after the existing bone GameObject instantiations:</p><p><code>bones[18] = (GameObject)Instantiate(Prefab_LeftHand_RightHand, Vector3.zero, Quaternion.identity) as GameObject;</code><br>
  <code>bones[18].name = (body.Id).ToString();</code>
 <br><code>bones[18].transform.SetParent(BoneRoot);</code></p>
  
  </li>
  <img src="https://user-images.githubusercontent.com/39998983/97363655-e908bd80-1870-11eb-8a1d-a7b1e053f202.PNG" alt="Search in finder" width="80%">
  <img src="https://user-images.githubusercontent.com/39998983/97363671-f160f880-1870-11eb-8b78-ddc390712a89.PNG" alt="Define a new bone" width="80%">
  <li><p>Now we're goint to define connecting points for our bone. We want to connect our bone between the left and right handjoints. To do this, <b>press Ctrl + F again and look up the comment "summary"</b> under this commment you will find several connecting points already defined. Define your connecting points by adding the following code underneath the existing joint connectors. Be sure to add a comment before the line of code explaining what connecting points you're defining!</p><p><code>new Bone(Astra.JointType.LeftHand, Astra.JointType.RightHand),</code></p></li>
   <img src="https://user-images.githubusercontent.com/39998983/97390291-6dc3fd80-18aa-11eb-8e4f-e0e1c2df6b2d.PNG" alt="Define joint connectors" width="80%">
   <li><p>Lastly, we need to attach our changes to Unity so that we can attach the bone image we'd like between hand joints. To do this, <b>click the button towards the top that says "Attach to Unity"</b> if there are any syntax errors, Visual Studio will flag them. If this happens, look back at the previous steps to make sure you input everything correctly!</p></li>
 <img src="https://user-images.githubusercontent.com/39998983/97391563-7a962080-18ad-11eb-8ccc-385a2e28431a.PNG" alt="Attach to Unity" width="100%">
 
 </ol>
 
<h4>Viewing Your Render</h4>
<p>Back in Unity, the renderer has been updated. We now have a new option to add an image! Click on the tiny circular icon to the right of the new option. This will open the image folder so that we can select the bone we'd like to attach between the left and right hand joints.</p>
<img src="https://user-images.githubusercontent.com/39998983/97394988-f85c2b00-18b1-11eb-95aa-08472480e613.PNG" alt="Attach to Unity" width="80%">
<p>Next, select a bone image for your render. For the puposes of this walkthrough, we selected "Test_FemurL."</p>
<img src="https://user-images.githubusercontent.com/39998983/97395466-052d4e80-18b3-11eb-93fa-23a293e10fdb.png" alt="Select bone image" width="80%">
<p>Now you should be able to view the new bone in your render! Switch back to the "Game" tab and press the play button. Notice how there's a new bone connecting the left and right hand joints!</p>
<img src="https://user-images.githubusercontent.com/39998983/97395938-0f038180-18b4-11eb-9187-9167b7a000be.png" alt="Render before and after" width="100%">

<h3>The Muscle Demo</h3>
<p>We just tried adding bones to the bone demo. Now let's try adding muscles to the muscle demo!</p>
<p>It should be really easy to add muscles since we have learned how to add bones. The concept is the same, the only difference is to replace the bone prefab we used with a muscle prefab. You can add the muscle to a different body part. But for simplicity, we will add a muscle to the same place as our example in the bone demo: between the left hand and the right hand.</p>

<h4>Getting started</h4>
<p>We have done this in the bone demo, please repeat the process. This time, open the muscle demo you have downloaded from github and navigate to Assets/Scenes/MuscleDemo.<p/>

<h4>Diving Into the Code</h4>
<p>You can try adding the muscle to a different body part, but we will add it in between the left hand and right hand again for this example. Please repeat the exact same process as we did from the previous bone demo example: adding a GameObject, instantiating the new GameObject, connecting points for the GameObject.<p/>

<h4>Viewing Your Render</h4>






<h2>Resources</h2>
<ul>
  <li>For engineering process documentation, utilize the <a href=" ">Engineering Design Process Notebook</a > as needed</li>
  <li>Watch this video from Code.org <a href="https://youtu.be/QvyTEx1wyOY">Computer is Changing Everything</a > to learn more about the computer science revolution and why you should pursue a career in computer science</li>
  <li>Watch <a href="https://youtu.be/O753uuutqH8">Software Engineering: Crash Course Computer Science #16</a > to learn more about software design and engineering</li>
</ul>



  

 
  




















 








