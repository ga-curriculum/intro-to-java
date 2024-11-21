<h1>
  <span class="headline">Intro to Java</span>
  <span class="subhead">Running Your First Java App</span>
</h1>

**Learning objective:** By the end of this lesson, students will be able to execute compiled Java files in the terminal.

## Running our file

Now that our function is ready to roll, how can we get it to run? With Java, we have two steps to complete:

- **Step 1**: Compile the code.
- **Step 2**: Run the code.

### Step 1: Compile

First, we must **compile** the code into bytecode for the Java Virtual Machine to run.

To accomplish this, we use the `javac` command-line app. It has this signature: `javac <file-name>`.

Go ahead and run this command now in the IntelliJ terminal, specifying our <code class="filepath">HowdyPartner.java</code> file in the command:

```bash
javac HowdyPartner.java
```

Always expect a compilation error or two (or 12), with a handy message pointing you to the exact line and nature of your problem.

You'll notice some contrast here if you're familiar with languages like JavaScript, where our code isn't evaluated for errors until it is run. In those languages, our file will run until we hit a broken line of code, at which time we will get an error. Java will detect these errors before our code ever runs.

The better method is up for debate, but many developers prefer Java's method. After all, wouldn't it be nice for a car to tell us our brakes are out and refuse to start rather than let us drive around without working brakes?

### Step 2: Run

When the file is successfully compiled, you should see a new <code class="filepath">HowdyPartner.class</code> file has been created: This is our compiled `class` - as denoted by the <code class="filepath">.class</code> extension.

Now we can **run** the code with the command `java` command:

```bash
java HowdyPartner
```

The big takeaway is that we can't run a file until it's compiled. A file with a <code class="filepath">.java</code> extension can't be executed with the `java` command, but a compiled file with the <code class="filepath">.class</code> extension can be.

<div class="activity discussion">
  <h2 class="title">Conclusion</h2>
  <span class="minutes">5 min</span>
</div>

Without looking at your notes, can you explain the different parts of the `main` method? Since we never called this method in our code, how did Java know to run the method when our app ran?
