<div class="section top">
  <h1>Kayla Ingebretsen</h1>
</div>

<div class="row-two">
  <div class="section">
    <h2><a href="https://github.com/kayinge17/CS-300-ABCU.git" target="_blank">Artifact 1</a></h2>
    <p>This artifact was created in CS 300: Analysis and Design in July/August 2024. It is a C++ program that reads course data from a CSV file and allows users to interact with that data through a menu-driven interface. The program enables users to load course information, display all courses in sorted order using a binary search tree, and search for a specific course by its ID.
    </p>
  </div>

  <div class="section">
    <h2><a href="https://github.com/kayinge17/CS-320-C_A_T.git" target="_blank">Artifact 2</a></h2> 
    <p>
    The selected artifact was created in CS 320: Software Testing and Automation
    in October of 2024. The original program was designed to create and manage
    three separate object types: contacts, appointments, and tasks. Each object
    type included validation logic and service classes to support CRUD operations.
    The artifact also included JUnit testing to verify object constraints and
    service methods functioned correctly.
  </p>
  </div>
</div>

<div class="section">
  <h2> <a href="https://youtu.be/xmt1T2k5ito" target="_blank">Code Review</a></h2>
  <p>
    This code review evaluates both artifacts, identifying strengths, weaknesses, and opportunities for improvement.
  </p>
 
</div>

<div class="row-three">
 <div class="section">
  <h2><a href="https://github.com/kayinge17/Enhancement-1-CS-300.git" target="_blank"">Enhancemen 1</a></h2>

  <p>
    This enhancement reimplements a C++ course management system in Python and improves
    data validation, usability, and overall program structure.
  </p>

  <p>
    
  </p>

  <hr>

  
  <h3>Justification and Improvements</h3>
  <p>
    I selected this artifact because it demonstrates my ability to design and implement
    efficient data structures, specifically a binary search tree, to solve a real-world
    data organization problem. It highlights my understanding of algorithms, file parsing,
    and user interaction through a structured interface.
  </p>

  <p>
    The enhancement strengthens the artifact by porting it from C++ to Python while preserving
    functionality and improving design. The course-loading process was simplified by
    preconfiguring the file path, reducing user error. Additional validation ensures course
    IDs and prerequisites meet expected formatting requirements before being added.
  </p>

  <ul>
    <li>Binary search tree implementation for efficient data storage and retrieval</li>
    <li>File input parsing with validation checks to ensure data integrity</li>
    <li>Menu-driven interface design with improved user flow</li>
    <li>Input validation to enhance reliability and security</li>
  </ul>

  <h3>Course Outcomes</h3>
  <p>
    This enhancement aligns with Course Outcome 4 by applying established and innovative
    techniques through cross-language implementation. It also aligns with Course Outcome 5
    by incorporating input validation to improve system security and reliability.
  </p>

  <h3>Reflection</h3>
  <p>
    Through enhancing this artifact, I gained a deeper understanding of the differences
    between C++ and Python, particularly in memory management and language structure.
    Python simplifies many operations, resulting in a more concise and readable implementation.
  </p>

  <p>
    A key challenge was handling user input and menu navigation without disrupting program
    flow. This required careful control flow design and reinforced the importance of
    defensive programming and thorough testing when designing interactive systems.
  </p>
</div>

  <div class="section">
    <h2><a href="https://github.com/kayinge17/Enhancement-2-CS-320.git" target="_blank">Enhancement 2</a></h2>
  <p>
    For this enhancement, I expanded the original artifact by introducing a new
    record management structure that organizes related objects together. The
    enhancement adds a ContactRecord and a ContactRecordService, allowing a contact
    to be associated with lists of appointments and tasks. This created a more
    organized and efficient way to manage related data.
  </p>

  <h3>Justification and Improvements</h3>
  <p>
    I selected this artifact because it shows my ability to work with data structures,
    object-oriented design, validation logic, and unit testing. It was a strong choice
    because the original project already managed multiple object types and provided
    a clear opportunity to improve how those objects were connected and retrieved.
  </p>

  <p>
    The original artifact demonstrated my ability to structure code logically, apply
    validation rules, and test functionality using JUnit. It included separate classes
    and service layers for contacts, appointments, and tasks, along with tests to verify
    correct behavior.
  </p>

  <p>
    The enhancement improved the artifact by introducing a HashMap-based structure
    that stores each contact as a key and links each contact to related appointments
    and tasks through a ContactRecord. This improved efficiency and organization by
    grouping related data instead of storing it independently.
  </p>

  <ul>
    <li>Implementation of a HashMap-based structure for efficient data access</li>
    <li>Grouping related objects into a unified record structure</li>
    <li>Development of new service methods for managing grouped data</li>
    <li>Expanded JUnit testing for valid and invalid scenarios</li>
  </ul>

  <p>
    Additional methods were created to add appointments and tasks to the correct
    contact record, retrieve grouped records, and delete contact data. New JUnit
    tests were also added to verify both correct and incorrect cases, including
    duplicate contacts, invalid identifiers, and null values.
  </p>

  <h3>Course Outcomes</h3>
  <p>
    This enhancement aligns with the outcome focused on designing and evaluating
    computing solutions using algorithmic principles and computer science practices.
    By creating structured relationships between contact, appointment, and task objects,
    I demonstrated my ability to improve how data is stored, retrieved, and managed.
  </p>

  <p>
    It also strengthened my understanding of software design and maintainability by
    requiring me to think beyond individual objects and focus on long-term data organization.
    The addition of JUnit testing further reinforced my ability to validate system behavior
    under both normal and incorrect conditions.
  </p>

  <h3>Reflection</h3>
  <p>
    Through this enhancement, I developed a deeper understanding of how to design systems
    that manage related data efficiently. Instead of treating objects as separate entities,
    I learned how to group them in a way that reflects real-world relationships.
  </p>

  <p>
    This process also reinforced the importance of designing scalable data structures and
    maintaining clean service layers. Expanding the test coverage helped me better understand
    how to validate system behavior and ensure reliability when modifying an existing program.
  </p>

  <p>
    Overall, this enhancement strengthened my ability to improve an existing system by
    redesigning its data structure and ensuring that changes were fully tested and reliable.
  </p>
</div>
    
  </div>

  <div class="section">
    <h2><a href="https://github.com/kayinge17/Enhancement-3-CS-320.git" target="_blank">Enhancement 3</a></h2>
   <p>
    This enhancement builds on both the original artifact and the work completed
    in Enhancement #2. For this third enhancement, I extended the grouped record
    structure by integrating a MongoDB database layer to persist the data. Instead
    of managing records only in memory, the program now stores them in a MongoDB
    “records” collection, where each document represents a contact and contains
    associated appointments and tasks as nested data.
  </p>

  <h3>Justification and Improvements</h3>
  <p>
    I selected this artifact because it demonstrates my ability to build on an
    existing software solution by applying data structures, backend logic,
    database integration, CRUD operations, and testing. It allowed me to extend
    the improvements made in Enhancement #2 into a more realistic, database-supported design.
  </p>

  <p>
    The original artifact demonstrated my ability to create separate classes and
    service layers, apply validation logic, and implement unit testing. This
    enhancement expands on that foundation by translating the grouped record
    structure into a MongoDB document model.
  </p>

  <p>
    Each record is stored in a single “records” collection, where documents include
    contact data along with nested arrays for appointments and tasks. This reflects
    the same grouped structure introduced in Enhancement #2, but now in a persistent
    database format.
  </p>

  <ul>
    <li>Integration of MongoDB for persistent data storage</li>
    <li>Implementation of NoSQL document-based data modeling</li>
    <li>CRUD operations including insert, find, update, push, pull, and delete</li>
    <li>Validation and exception handling for database operations</li>
    <li>JUnit testing for both valid and invalid database scenarios</li>
  </ul>

  <p>
    The enhancement required implementing database operations with filters to locate
    specific records, along with validation to handle invalid inputs such as null
    values or non-existent records. Additional JUnit tests were created to verify
    that records could be stored, updated, retrieved, and deleted correctly.
  </p>

  <h3>Course Outcomes</h3>
  <p>
    This enhancement aligns strongly with outcomes focused on designing and evaluating
    computing solutions and using appropriate tools and technologies to implement them.
    By extending both the original artifact and the grouped record structure, I
    demonstrated my ability to build on an existing system in a meaningful and
    structured way.
  </p>

  <p>
    The enhancement also strengthened my understanding of backend development and
    data modeling by requiring me to connect application logic with persistent
    storage. The use of JUnit testing further reinforced my ability to validate
    database operations under both normal and incorrect conditions.
  </p>

  <h3>Reflection</h3>
  <p>
    Through this enhancement, I gained a deeper understanding of how to design and
    implement a backend system that integrates application logic with a database.
    I learned how to translate object-oriented structures into a NoSQL document
    model while maintaining consistency across the system.
  </p>

  <p>
    This process also highlighted the importance of data modeling and ensuring that
    the structure used in the application aligns with how data is stored and retrieved
    in the database. Managing CRUD operations at the database level required careful
    attention to validation, error handling, and testing.
  </p>

  <p>
    Overall, this enhancement strengthened my ability to extend an application into
    a full backend system, demonstrating growth in database integration, data modeling,
    and software design.
  </p>
    
  </div>

<div class="section bottom">
  <h2>Professional Self-Assessment</h2>
  <p>
    TBD
  </p>
</div>
