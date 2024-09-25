# **Playwright Tutorials with JAVA**
### Table of Contents

1. [Overview](#Overview)
2. [Getting Started](#Getting-Started)

    - [Prerequisites](#prerequisites)
    - [Installation](#installation)

      - [Java JDK](#java-jdk)
      - [IDE](#ide)
      - [Apache Maven](#apache-maven)

    - [Setting Up Java JDK](#setting-up-java-jdk)
    - [Setting Up Spring Tools](#setting-up-spring-tools)
    - [Installing Apache Maven](#installing-apache-maven)

11. [Built With](#built-with)
12. [Installation Steps](#installation-steps)   
21. [Step Wise Details](#step-wise-details)

    - [Launching Browsers](#00---launching-browsers)
    - [Launching Browsers In Headless Mode](#01---launching-browsers-in-headless-mode)
    - [Locators](#02---locators)
    - [WebDriver Browser Commands](#03---webdriver-browser-commands)
    - [WebDriver Navigation Commands](#04---webdriver-navigation-commands)
    - [Waits](#05---waits)
    - [Automate Radio Button](#06---automate-radio-button)
    - [Automate Checkbox](#07---automate-checkbox)
    - [DropDown](#08---dropdown)
    - [Alerts](#09---alerts)
    - [Form WebElement Commands](#10---form-webelement-commands)
    - [Mouse Events](#11---mouse-events)
    - [Keyboard Events](#12---keyboard-events)
    - [Browser Tab](#13---browser-tab)
    - [Browser Window](#14---browser-window)
    - [Frame](#15---frame)
    - [Assertion](#16---assertion)
    - [Web Table](#17---web-table)
    
38. [Acknowledgments](#acknowledgments)
39. [Contact](#contact)

### Overview
This repository serves as a comprehensive guide to working with Playwright using Java. Whether you're a beginner looking to get started with Playwrigth for automated testing or an experienced developer seeking advanced browser handling techniques, this repository has something for everyone.

### Getting Started
Follow these steps to set up your development environment and start using Playwrigth with Java

### Prerequisites

1. [Java JDK](https://www.oracle.com/java/technologies/javase-jdk15-downloads.html)
2. Choose one of the following IDE:
    - [Eclipse](https://www.eclipse.org/downloads/packages/release/2024-03/r/eclipse-ide-java-developers)
    - [IntelliJ IDEA](https://www.jetbrains.com/idea/download/)
    - [Spring Tools](https://spring.io/tools)
3. [Apache Maven](https://maven.apache.org/download.cgi)

### Installation

1. Java JDK
    - Download the installer from the [Oracle Java SE Downloads](https://www.oracle.com/java/technologies/javase-jdk15-downloads.html) page.
    - Run the installer and set up the JDK.
2. IDE
    - Download and install your preferred IDE.
3. Apache Maven
    - Download Apache Maven from the [official website](https://maven.apache.org/download.cgi).
    - Follow installation instructions.
  
### Setting Up Java JDK

1. Download the JDK installer from Oracle.
2. Run the installer and select your installation folder.
3. Set up JAVA_HOME and PATH environment variables:
         - Open System Properties.
         - Navigate to Environment Variables.
         - Add JAVA_HOME with the JDK installation path.
         - Update the PATH variable to include %JAVA_HOME%\bin.
4. Verify Java installation by running java --version in a terminal.

### Setting Up Spring Tools

1. Download Spring Tools from the [official website](https://spring.io/tools).
2. Run the installer and select the package to install.
3. Choose your installation folder and complete the setup.
4. Launch Spring Tools to start using it.

### Installing Apache Maven

1. Check if you have Java installed by running java --version.
2. Download Apache Maven from the [official website](https://maven.apache.org/download.cgi).
3. Extract the archive to your desired location.
4. Set up M2_HOME and MAVEN_HOME environment variables:
    - Create M2_HOME and point it to the Maven installation directory.
    - Update the PATH variable to include %M2_HOME%\bin.
5. Verify Maven installation by running mvn --version in a terminal.

### Built With

1. [Java JDK](https://www.oracle.com/java/) - Java Development Kit
2. [Spring Tools](https://spring.io/tools/) - IDE for Spring applications
3. [Apache Maven](https://maven.apache.org/) - Dependency Management

### Installation Steps
To start using the framework:

1. [Fork]() the repository.
2. Clone, i.e, download your copy of the repository to your local machine using
```
git clone https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java.git
```
3. Import the project into your preferred IDE (Eclipse, IntelliJ IDEA, or Spring Tools).
4. Make any desired changes or additions to the project.

##### Maven Dependencies

###### Playwright TestNG

```xml
<dependencies>
		<!-- https://mvnrepository.com/artifact/com.microsoft.playwright/playwright -->
        <dependency>
            <groupId>com.microsoft.playwright</groupId>
            <artifactId>playwright</artifactId>
            <version>1.43.0</version>
        </dependency>

		<!-- https://mvnrepository.com/artifact/org.testng/testng -->
		<dependency>
			<groupId>org.testng</groupId>
			<artifactId>testng</artifactId>
			<version>7.8.0</version>
			<scope>test</scope>
		</dependency>
</dependencies>
```

## Step Wise Details

### 00 - Launching Browsers
- 00 - 00 [How to run Playwright Tests using Chrome?](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/browserhanding/ChromeBrowser.java) 
- 00 - 01 [How to run Playwright Tests using Firefox?](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/browserhanding/FirefoxBrowserInPlaywright.java)
- 00 - 02 [How to run Playwright Tests using Edge?](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/browserhanding/EdgeBrowserInPlaywright.java)
- 00 - 03 [How to run Playwright Tests using Safari?](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/browserhanding/SafariBrowserInPlaywright.java)
- 00 - 04 [How to Configure cross browser in Playwright?](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/browserhanding/CrossBrowserConfiguration.java)

### 01 - Launching Browsers In Headless Mode
- 01 - 00 [How to run Chrome tests in headless mode in Playwright?](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/headlessbrowserhandle/HeadlessChromeBrowserInPlaywright.java)
- 01 - 01 [How to run Firefox tests in headless mode in Playwright?](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/headlessbrowserhandle/HeadlessFirefoxBrowserInPlaywright.java)
- 01 - 02 [How to run Edge tests in headless mode in Playwright?](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/headlessbrowserhandle/HeadlessEdgeBrowserInPlaywright.java)

### 02 - Locators
- 02 - 00 [Locate by ID](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/locators/LocateByIDAttribute.java)
- 02 - 01 [Locate by Name](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/locators/LocateByNameAttribute.java)
- 02 - 02 [Locate by Class Name](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/locators/LocateByClassNameAttribute.java)
- 02 - 03 [Locate by CSS Selector](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/locators/LocateByCssSelectorAttribute.java)
- 02 - 04 [Locate by Link Text](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/locators/LocateByLinkTextAttribute.java)
- 02 - 05 [Locate by Tag Name](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/locators/LocateByTagNameAttribute.java)
- 02 - 06 [Locate by Relative XPath](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/locators/dynamicxpath/LocateByRelativeXPath.java)
- 02 - 07 [Locate by Text](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/locators/dynamicxpath/LocateByText.java)
- 02 - 08 [Locate by Starts With](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/locators/dynamicxpath/LocateByStartsWith.java)
- 02 - 09 [Locate by Preceding](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/locators/dynamicxpath/LocateByPreceding.java)
- 02 - 10 [Locate by Position](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/locators/dynamicxpath/LocateByPosition.java)
- 02 - 11 [Locate by OR Expression](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/locators/dynamicxpath/LocateByOrExpression.java)
- 02 - 12 [Locate by AND Expression](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/locators/dynamicxpath/LocateByAndExpression.java)
- 02 - 13 [Locate by Contains](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/locators/dynamicxpath/LocateByContains.java)
- 02 - 14 [Locate by Last](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/locators/dynamicxpath/LocateByLast.java)

### 03 - WebDriver Browser Commands
- 03 - 00 [Retrieve Title Of Current WebPage](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/webdrivergetcommands/RetrieveTitleOfCurrentWebPage.java)
- 03 - 01 [Retrieve Current URL Of Current WebPage](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/webdrivergetcommands/RetrieveCurrentURLOfCurrentWebPage.java)
- 03 - 02 [Retrieve Attribute Value By Get Attribute](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/webdrivergetcommands/RetrieveAttributeValueByGetAttributeMethod.java)
- 03 - 03 [Retrieve The Class Object](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/webdrivergetcommands/RetrieveTheClassObject.java)
- 03 - 04 [Retrieve Text By Get](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/webdrivergetcommands/RetrieveTextByGetTextMethod.java)
- 03 - 05 [Retrieve Page Source Of Current WebPage](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/webdrivergetcommands/RetrievePageSourceOfCurrentWebPage.java)
- 03 - 06 [Retrieve Location By Get Location](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/webdrivergetcommands/RetrieveLocationByGetLocationMethod.java)

### 04 - WebDriver Navigation Commands
- 04 - 00 [Navigate To](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/webdrivernavigationcommands/NavigateToCommand.java)
- 04 - 01 [Refresh](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/webdrivernavigationcommands/RefreshCommand.java)
- 04 - 02 [Back](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/webdrivernavigationcommands/BackCommand.java)
- 04 - 03 [Forward](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/webdrivernavigationcommands/ForwardCommand.java)

### 05 - Waits
- 05 - 00 [Explicit](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/waits/ExplicitWait.java)
- 05 - 01 [Implicit](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/waits/ImplicitWait.java)

### 06 - Automate Radio Button
- 06 - 00 [Single Radio Button Selection](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/radiobuttonhandling/SelectRadioButton.java)
- 06 - 01 [Group Radio Button Selection](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/radiobuttonhandling/SelectRadioButtonDynamic.java)

### 07 - Automate Checkbox
- 07 - 00 [Select Checkbox By ID](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/checkboxhandling/SelectCheckboxByID.java)
- 07 - 01 [Select Checkbox By XPath](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/checkboxhandling/SelectCheckboxByXPath.java)
- 07 - 02 [Select Multiple Checkboxes](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/checkboxhandling/SelectMultiplesCheckbox.java)
- 07 - 03 [Unselect Checkbox By ID](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/checkboxhandling/unselectCheckboxByID.java)
- 07 - 04 [Unselect Checkbox By XPath](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/checkboxhandling/UnselectCheckboxByXPath.java)
- 07 - 05 [Unselect Multiple Checkboxes](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/checkboxhandling/UnselectMultiplesCheckbox.java)

### 08 - DropDown
- 08 - 00 [Select By Index](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/dropdownhandling/SelectByIndex.java)
- 08 - 01 [Select By Value](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/dropdownhandling/SelectByValue.java)
- 08 - 02 [Select By Visible Text](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/dropdownhandling/SelectByVisibleText.java)
- 08 - 03 [Fetch List of options in dropdown](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/dropdownhandling/FetchAllOptions.java)
- 08 - 04 [DeSelect By Index](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/dropdownhandling/DeselectByIndex.java)

### 09 - Alerts
- 09 - 00 [Accept Simple Alert](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/alerthandling/AcceptSimpleAlert.java)
- 09 - 01 [Accept Confirm Alert](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/alerthandling/AcceptConfirmAlert.java)
- 09 - 02 [Accept Prompt Alert](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/alerthandling/AcceptPromptAlert.java)
- 09 - 03 [Fetch Text Of Prompt Alert](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/alerthandling/GetTextOfPromptAlert.java)
- 09 - 04 [Send Text In Prompt Alert](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/alerthandling/SendTextPromptAlert.java)
- 09 - 05 [Reject Confirm Alert](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/alerthandling/DismissConfirmAlert.java)
- 09 - 06 [Reject Prompt Alert](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/alerthandling/DismissPromptAlert.java)

### 10 - Form WebElement Commands
- 10 - 00 [Sendkeys](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/formwebelementcommands/SendKeysMethod.java)
- 10 - 01 [Clear](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/formwebelementcommands/ClearMethod.java)
- 10 - 02 [Click](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/formwebelementcommands/ClickMethod.java)
- 10 - 03 [Submit](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/formwebelementcommands/SubmitMethod.java)

### 11 - Mouse Events
- 11 - 00 [Click](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/mouseevents/Click.java)
- 11 - 01 [Click And Hold](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/mouseevents/ClickAndHold.java)
- 11 - 02 [Double Click](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/mouseevents/DoubleClick.java)
- 11 - 03 [Drag And Drop](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/mouseevents/DragAndDrop.java)
- 11 - 04 [Drag And Drop By Offset](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/mouseevents/DragAndDropByOffset.java)
- 11 - 06 [Move To Element](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/mouseevents/Hover.java)
- 11 - 07 [Right Click](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/mouseevents/RightClick.java)

### 12 - Keyboard Events
- 12 - 00 [Keyboard Events](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/keyboardevents/KeyboardEvents.java)

### 13 - Browser Tab
- 13 - 00 [Create New Tab](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/tabhandling/CreateNewTab.java)
- 13 - 01 [Count The Tabs](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/tabhandling/CountTheTabs.java)
- 13 - 02 [Switch To New Tab](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/tabhandling/SwitchToNewTab.java)
- 13 - 03 [Switching One Tab To Another](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/tabhandling/SwitchingOneTabToAnother.java)

### 14 - Browser Window
- 14 - 00 [Create New Window](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/windowhandling/CreateNewWindow.java)
- 14 - 01 [Count The Window](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/windowhandling/CountTheWindows.java)
- 14 - 02 [Switch To New Window](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/windowhandling/SwitchToNewWindow.java)
- 14 - 03 [Switching One Window To Another](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/windowhandling/SwitchingOneWindowToAnother.java)

### 15 - Frame
- 15 - 00 [Count The Total Number Of IFrames](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/iframehandling/CountTotalNumberOfIFrames.java)
- 15 - 01 [Switch To Frames By ID](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/iframehandling/SwitchToFramesByID.java)
- 15 - 02 [Switch To Frames By Index](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/iframehandling/SwitchToFramesByIndex.java)
- 15 - 03 [Switch To Frames By Name](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/iframehandling/SwitchToFramesByName.java)
- 15 - 04 [Switch To Frames By WebElement](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/iframehandling/SwitchToFramesByWebElement.java)
- 15 - 05 [Switch Back To Default](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/iframehandling/SwitchBackToMainPage.java)

### 16 - Assertion
- 16 - 00 [Assert Equals](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/assertions/AssertEquals.java)
- 16 - 01 [Assert False](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/assertions/AssertFalse.java)
- 16 - 02 [Assert Not Equals](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/assertions/AssertNotEquals.java)
- 16 - 03 [Assert Not Null](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/assertions/AssertNotNull.java)
- 16 - 04 [Assert True](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/assertions/AssertTrue.java)
- 16 - 05 [Soft Assertion](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/assertions/SoftAssertion.java)

### 17 - Web Table
- 17 - 00 [Fetch Table Heading](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/webtablehandling/FetchTableHeading.java)
- 17 - 01 [Count Number Of Rows And Columns](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/webtablehandling/NumberOfRowsAndColumns.java)
- 17 - 02 [Fetch Cell Value Of Particular Row And Column](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/webtablehandling/FetchCellValueOfParticularRowAndColumn.java)
- 17 - 03 [Get Maximum Price In Column](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java/blob/main/src/test/java/webtablehandling/GetMaximumPriceInColumn.java)

### Acknowledgments
Special thanks to the contributors and the Playwright community for their valuable resources and tutorials.

### Contact
For questions or feedback, please feel free to reach out:

1. Maintainer: [MD Muhiuddin]()
2. Project Link:[Playwright-Tutorials-Java](https://github.com/ebrahimhossaincse/Playwright-Tutorials-Java) 