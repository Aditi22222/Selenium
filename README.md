# Selenium Documentation
# Table of Contents

1. [Introduction](#introduction)
2. [Basic Setup For Selenium(JDK, Maven Project, Eclipse )](#Basic-Setup-For-Selenium)
3. [Open browser using Selenium(WebDriver , Eclipse )](#Open-browser-using-Selenium)
4. [Write Testcase, step(TestNG, Installation, Configure)](#Write-Testcase-step)
5. [Locators In Selenium (TestNG Priority Attribute)](#Locators-In-Selenium)
6. [Automating Shopping Website  In Selenium ](#Automating-Facebook-In-Selenium) 

# Introduction to Selenium

Selenium stands as a cornerstone in the realm of automated web testing and browser automation. It's a suite of tools and libraries designed to simplify and streamline the process of testing web applications across different browsers and platforms. Since its inception, Selenium has evolved into a robust and versatile framework, empowering developers and testers to automate various web-related tasks efficiently.

At its core, Selenium enables users to interact with web elements, simulate user actions, and validate expected behaviors, all programmatically. Whether it's filling out forms, clicking buttons, navigating through pages, or verifying content, Selenium provides the necessary tools to replicate user interactions with precision and reliability.

One of Selenium's key strengths lies in its cross-browser compatibility, allowing tests to be executed seamlessly across popular browsers like Chrome, Firefox, Safari, and Internet Explorer. This ensures consistent behavior across different browser environments, crucial for ensuring the compatibility and reliability of web applications in today's diverse web landscape.

Moreover, Selenium supports multiple programming languages, including Java, Python, C#, Ruby, JavaScript, and more, making it accessible to a wide range of developers with varying skill sets and preferences. This flexibility enables teams to leverage their existing programming expertise and seamlessly integrate automated testing into their development workflows.

Beyond its primary use case in automated testing, Selenium finds applications in web scraping, data extraction, and browser automation for various tasks such as performance monitoring, content validation, and repetitive administrative tasks.

In essence, Selenium empowers developers and testers to accelerate the testing process, enhance the quality and reliability of web applications, and ultimately deliver better user experiences. Its rich feature set, combined with a vibrant community and extensive documentation, makes Selenium a go-to choice for automating web-related tasks in today's fast-paced software development landscape.

# Basic Setup For Selenium(JDK, Maven Project, Eclipse 
To set up a basic Selenium project using JDK, Maven, and Eclipse, follow these steps:

### Step 1: Install JDK (Java Development Kit)

1. Download and install the latest version of JDK from the official Oracle website.
2. Set up the JAVA_HOME environment variable to point to the JDK installation directory.
   
   ![Screenshot 2024-03-07 102822](https://github.com/Aditi22222/Selenium/assets/162342704/190b5212-a3eb-4b0f-bec3-c53d29395cc2)


### Step 2: Install Eclipse IDE

1. Download and install the Eclipse IDE for Java Developers from the Eclipse Foundation website.
2. Launch Eclipse and set up any necessary preferences.

### Step 3: Create a Maven Project

1. Open Eclipse IDE.
2. Go to "File" -> "New" -> "Other...".
3. In the wizard, select "Maven" -> "Maven Project" and click "Next".
4. Choose "Create a simple project (skip archetype selection)" and click "Next".
5. Enter the Group Id, Artifact Id, and Version for your project. Click "Finish" to create the Maven project.

### Step 4: Add Selenium Dependencies

1. In the Eclipse project explorer, right-click on your Maven project and select "Properties".
2. In the properties dialog, navigate to "Java Build Path" -> "Libraries" -> "Add External JARs...".
3. Add the Selenium dependencies to your project. You can download the Selenium Java bindings from the Selenium website or use Maven to manage dependencies automatically.

### Step 5: Write Your Selenium Tests

1. Create a new Java class within your Maven project.
2. Write your Selenium test code using the Selenium WebDriver API.
3. Make sure to include necessary import statements for Selenium classes.

### Step 6: Run Your Selenium Tests

1. Right-click on your test class and select "Run As" -> "JUnit Test".
2. Eclipse will execute your Selenium tests using the configured WebDriver and display the results in the JUnit view.

That's it! You've now set up a basic Selenium project using JDK, Maven, and Eclipse. You can expand upon this setup by adding additional dependencies, configuring test suites, and integrating with other testing frameworks as needed.
