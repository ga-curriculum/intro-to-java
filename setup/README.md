<h1>
  <span class="headline">Intro to Java</span>
  <span class="subhead">Setup</span>
</h1>

<div class="timed-section">
  <h2>Setup</h2>
  <span class="minutes">5 min</span>
</div>

Launch the IntelliJ IDEA application.

Select the **New Project** option.

Name the project `into-to-java`.

Create the project in the <code class="filepath">~/code/ga/lectures</code> directory.

> ⚠️ Windows users, the <code class="filepath">lectures</code> directory is likely at this location on your device: <code class="filepath">C:\Users\username\code\ga\lectures</code> (replacing `username` with your username). Create the project in that directory instead.

Ensure the JDK used is **temurin-17**. This should be the default setting when starting a new project. If it's not, alert your instructor.

Ensure that the **Add sample code** option is not checked.

After confirming the **New project** window looks similar to the screenshot below, select the **Create** button.

![A new project being created with the appropriate values - intro-to-java is the project name, it's located in the ~/code/ga/lectures directory, the JDK is temurin-17, and the add sample code option is has been unchecked.](./assets/new-project-complete.png)

If everything goes according to plan, you'll see a new window like the one below.

![Our brand new project created in IntelliJ IDEA](./assets/intro-to-java-project.png)

Take the opportunity to note that the new project comes with a very basic file structure:

- <code class="filepath">.idea</code> holds some workspace configuration settings for the IntelliJ IDEA app.
- <code class="filepath">src</code> holds the Java code we write.
- A <code class="filepath">.gitignore</code> file with some sensible defaults pre-configured.

With that done, we're ready to write our first Java code!
