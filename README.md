<!-- This is your README.md file -->

<h1 align="center">ERP Hybrid Framework</h1>

<p align="center">
  Welcome to the <strong>ERP Hybrid Framework</strong>! This framework leverages the power of both Data-Driven and Keyword-Driven approaches to provide a flexible and scalable solution for automating ERP system testing.
</p>

---

<h2>🚀 Features</h2>

<ul>
  <li><strong>Hybrid Approach:</strong> Combines Data-Driven and Keyword-Driven methodologies.</li>
  <li><strong>Modular Design:</strong> Separate modules for utilities, common functions, and test drivers.</li>
  <li><strong>Maven Integration:</strong> Uses Maven for project build management.</li>
  <li><strong>Excel Support:</strong> Flexible handling of test data using Excel files.</li>
  <li><strong>Reusable Components:</strong> Includes reusable libraries for handling common tasks like reading Excel files and environment properties.</li>
</ul>

---

<h2>📂 Project Structure</h2>

<pre>
ERP_Hybrid
│
├── src
│   ├── main
│   │   ├── java
│   │   └── resources
│   └── test
│       ├── java
│       │   ├── commonFunctions
│       │   │   └── FunctionLibrary.java
│       │   ├── driverFactory
│       │   │   ├── AppTest.java
│       │   │   └── DriverScript.java
│       │   └── utilities
│       │       └── ExcelFileUtil.java
│       └── resources
│
├── CaptureData
│   ├── customernumber.txt
│   ├── StockNumber.txt
│   └── suppliernumber.txt
│
├── FileInput
│   └── Controller.xlsx
│
├── FileOutput
│   └── HybridResults.xlsx
│
├── PropertyFiles
│   └── Environment.properties
│
├── target
│   ├── generated-sources
│   ├── generated-test-sources
│   ├── maven-status
│   ├── Reports
│   └── surefire-reports
│
└── pom.xml
</pre>

---

<h2>📦 Dependencies</h2>

Make sure you have the following installed:

<ul>
  <li><strong>Java</strong> (version 8 or above)</li>
  <li><strong>Maven</strong> (latest stable version)</li>
</ul>

<h3>📚 Libraries Used</h3>
<ul>
  <li><strong>Selenium WebDriver</strong></li>
  <li><strong>Apache POI</strong> (for Excel file handling)</li>
  <li><strong>TestNG</strong> (for testing)</li>
  <li><strong>Maven Surefire Plugin</strong> (for running tests)</li>
</ul>

---

<h2>🛠️ How to Run the Tests</h2>

<ol>
  <li><strong>Clone the repository:</strong>
    <pre>
    git clone https://github.com/yuvrajchavale/Hybrid-With-Maven-.git
    cd ERP_Hybrid
    </pre>
  </li>
  <li><strong>Install the dependencies:</strong>
    <pre>
    mvn clean install
    </pre>
  </li>
  <li><strong>Run the tests:</strong>
    <pre>
    mvn test
    </pre>
  </li>
</ol>

---

<h2>📝 Test Data Structure</h2>

<p>
Test data is stored in the <code>CaptureData</code> and <code>FileInput</code> directories. This data is read dynamically during test execution to drive different test cases.
</p>

---

<h2>📊 Test Results</h2>

<p>
After execution, test results are automatically generated and saved in the <code>FileOutput</code> directory as <strong>HybridResults.xlsx</strong>. Detailed execution reports can be found in the <code>target/surefire-reports</code> directory.
</p>

---

<h2>🌐 Contribution Guidelines</h2>

<p>
Feel free to contribute to the project! Whether it's reporting a bug, proposing a new feature, or submitting a pull request, we appreciate all contributions.
</p>

<ol>
  <li>Fork the repo</li>
  <li>Create your feature branch (<code>git checkout -b feature/fooBar</code>)</li>
  <li>Commit your changes (<code>git commit -am 'Add some fooBar'</code>)</li>
  <li>Push to the branch (<code>git push origin feature/fooBar</code>)</li>
  <li>Create a new Pull Request</li>
</ol>

---

<h2>🎨 Technologies Used</h2>

<ul>
  <li><strong>Java</strong></li>
  <li><strong>Maven</strong></li>
  <li><strong>Selenium WebDriver</strong></li>
  <li><strong>TestNG</strong></li>
  <li><strong>Apache POI</strong></li>
</ul>

---

<h2>🌟 Show Your Support</h2>

<p>
If you like this framework, please give it a ⭐ on GitHub!
</p>
