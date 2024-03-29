
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

    ![Screenshot 2024-03-07 103403](https://github.com/Aditi22222/Selenium/assets/162342704/ca0c9b41-4892-41ef-b6a1-2857b08f8c6a)

### Step 3: Create a Maven Project

1. Open Eclipse IDE.
2. Go to "File" -> "New" -> "Other...".
3. In the wizard, select "Maven" -> "Maven Project" and click "Next".
4. Choose "Create a simple project (skip archetype selection)" and click "Next".
5. Enter the Group Id, Artifact Id, and Version for your project. Click "Finish" to create the Maven project.

    ![Screenshot 2024-03-07 103801](https://github.com/Aditi22222/Selenium/assets/162342704/0e6e7e35-de12-42c7-84b1-5faf3c325c66)

    ![Screenshot 2024-03-07 103844](https://github.com/Aditi22222/Selenium/assets/162342704/46ab9d6c-395c-46ae-b6fa-3b02eb705d90)
   

### Step 4: Add Selenium Dependencies

1. **Save the File:** After adding the dependencies, save the `pom.xml` file.

2. **Update Maven Project:** Right-click on your Maven project in the project explorer, navigate to "Maven" -> "Update Project...". This will update the project with the newly added dependencies.

3. **Wait for Dependencies to Download:** Maven will automatically download the required libraries and manage them for you. Wait for Maven to finish downloading the dependencies.

4. **Verify Dependencies:** Once the dependencies are downloaded successfully, you can verify that they are added to your project by expanding the "Maven Dependencies" folder in the project explorer.


![Screenshot 2024-03-07 111936](https://github.com/Aditi22222/Selenium/assets/162342704/4b2111f2-4cff-4db6-85f8-66498d1ca426)

### Step 5: Write Your Selenium Tests

1. Create a new Java class within your Maven project.
2. Write your Selenium test code using the Selenium WebDriver API.
3. Make sure to include necessary import statements for Selenium classes.

![Screenshot 2024-03-07 114828](https://github.com/Aditi22222/Selenium/assets/162342704/68e0fece-95e4-49fe-9964-c0e9ea4daf0b)

![Screenshot 2024-03-07 115548](https://github.com/Aditi22222/Selenium/assets/162342704/a190ecd3-16df-4d52-a4d1-ab36b55f9f18)

# Open browser using Selenium(WebDriver , Eclipse)

import org.openqa.selenium.WebDriver;
import org.openqa.selenium.chrome.ChromeDriver;

public class OpenBrowser {
    public static void main(String[] args) {
       
         1. Set the system property to specify the location of the ChromeDriver executable
        System.setProperty("webdriver.chrome.driver", "C:\\salanium testing\\chromedriver\\chromedriver-win32\\chromedriver.exe");
        
        2. Initialize a new instance of the ChromeDriver class
        WebDriver driver = new ChromeDriver();
        
         3. Open a new browser window
        driver.get("https://www.example.com");
    }
}
 # Write Testcase, step(TestNG, Installation, Configure)

1. **Open Eclipse IDE:**
   - Launch the Eclipse IDE on your computer.

2. **Access the Eclipse Marketplace:**
   - Go to `Help` > `Eclipse Marketplace...` from the top menu bar.

3. **Search for TestNG:**
   - In the Eclipse Marketplace dialog, type "TestNG" into the search bar.

4. **Select TestNG from Search Results:**
   - From the search results, find "TestNG for Eclipse" and click on it.

5. **Install TestNG:**
   - Click on the `Go to the marketplace` button.
   - Click on the `Install` button next to "TestNG for Eclipse".

6. **Review Installation Details:**
   - Review the details of the installation including the software being installed and its dependencies.

7. **Accept License Agreement:**
   - Accept the terms of the license agreement and click `Finish`.

8. **Restart Eclipse:**
   - Once the installation is complete, Eclipse will prompt you to restart.
   - Click `Yes` to restart Eclipse.

9. **Verify TestNG Installation:**
   - After restarting Eclipse, create a new Java project or open an existing one.
   - Right-click on the project, go to `Properties` > `TestNG`.
   - Verify that TestNG is listed as one of the testing frameworks.

10. **TestNG is Installed Successfully:**
    - Congratulations! You have successfully installed TestNG in Eclipse via the Eclipse Marketplace.

![Screenshot 2024-03-07 144713](https://github.com/Aditi22222/Selenium/assets/162342704/9c1b3c06-7987-4801-8d8a-f84db51fa6c2)

![Screenshot 2024-03-07 145304](https://github.com/Aditi22222/Selenium/assets/162342704/cdfd3354-5d21-4c8a-9fb4-acfb1a3022d1)

# Locators In Selenium (TestNG Priority Attribute)

Selenium WebDriver is a powerful tool for automating web applications. Locators are used to identify elements on a web page, and TestNG's priority attribute allows you to prioritize the execution order of test methods.

#### Locating Elements with Selenium WebDriver

1. **ID Locator:**
   - Use `driver.findElement(By.id("element_id"))` to locate elements by their ID attribute.

2. **Name Locator:**
   - Use `driver.findElement(By.name("element_name"))` to locate elements by their Name attribute.

3. **Class Name Locator:**
   - Use `driver.findElement(By.className("element_class"))` to locate elements by their Class Name attribute.

4. **Tag Name Locator:**
   - Use `driver.findElement(By.tagName("tag_name"))` to locate elements by their HTML tag.

5. **Link Text Locator:**
   - Use `driver.findElement(By.linkText("link_text"))` to locate anchor elements by their visible text.

6. **Partial Link Text Locator:**
   - Use `driver.findElement(By.partialLinkText("partial_link_text"))` to locate anchor elements by partial visible text.

7. **XPath Locator:**
   - Use `driver.findElement(By.xpath("xpath_expression"))` to locate elements using XPath.

8. **CSS Selector Locator:**
   - Use `driver.findElement(By.cssSelector("css_selector"))` to locate elements using CSS selectors.

#### Using TestNG Priority Attribute

The priority attribute in TestNG allows you to prioritize the order of test method execution.

1. **Specify Priority in TestNG Annotations:**
   - Use the `priority` attribute in `@Test` annotation to specify the execution order of test methods.
   - TestNG will execute the test methods in ascending order of their priority values.

![Screenshot 2024-03-07 145816](https://github.com/Aditi22222/Selenium/assets/162342704/23ca662e-6c7f-4517-b954-dfc61088eea6)
 
# Automating Shopping Website  In Selenium
### Selenium WebDriver Test Case Steps with Bug

#### Test Case: Perform Login, Remove Item from Cart, and Proceed to Checkout

1. **Set Up WebDriver and Navigate to Website:**
   - Set up Chrome WebDriver using `webdriver.chrome.driver` system property.
   - Initialize WebDriver and navigate to the website "https://www.saucedemo.com".
   - Maximize the browser window.

2. **Login to the Application:**
   - Locate the username field by CSS selector and enter the username "standard_user".
   - Locate the password field by CSS selector and enter the password "secret_sauce".
   - Locate the login button by CSS selector and click it.

3. **Remove Item from Cart:**
   - Locate the "Remove" button for the item by its ID ("remove-sauce-labs-backpack").
   - Click the "Remove" button.

4. **Proceed to Checkout:**
   - Locate the "Checkout" button by its ID ("checkout").
   - Click the "Checkout" button.

5. **Bug: Unable to Proceed to Checkout After Item Removal:**
   - Observation: After removing the item from the cart, the "Proceed to Checkout" button does not function as expected.
   - Expected Result: Users should be able to proceed to checkout after removing an item from the cart.
   - Impact: Users cannot complete purchases, leading to potential loss of sales and negative user experience.
   - Steps to Reproduce:
     - Click the "Remove" button for an item in the cart.
     - Attempt to click the "Checkout" button.
   - Workaround: Manually verify the checkout process or investigate further to fix the issue.
   - Note: Additional investigation and debugging are required to identify and resolve the root cause of the issue.

6. **Clean Up:**
   - Quit the WebDriver instance.

#### Note:
- Each step performs an action on the web page using Selenium WebDriver.
- Thread.sleep() is used to introduce delays for demonstration purposes. In practice, it's better to use explicit waits.
- CSS selectors and IDs are used to locate elements on the web page.

![Screenshot 2024-03-07 151615](https://github.com/Aditi22222/Selenium/assets/162342704/ddcd28a9-7e0e-4937-9282-2ff58d679fd2)

![Screenshot 2024-03-07 151657](https://github.com/Aditi22222/Selenium/assets/162342704/81476d95-0995-436a-9cd0-04b082f38746)

![Screenshot 2024-03-07 151707](https://github.com/Aditi22222/Selenium/assets/162342704/2b10879e-01b0-4a75-ba64-c1c09a9745e1)
# Output 

![Screenshot 2024-03-07 150907](https://github.com/Aditi22222/Selenium/assets/162342704/2c3b48f6-9352-4655-be10-8c005e54df12)

