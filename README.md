# Project Issue-Tracker 

<ol>
<li>Shows the list of projects in progress.
  <ul>
    <li>Show a list of projects.</li>
    <li>Button to create a new Project.</li>  
  </ul>
 </li>
<li>While creating project it accepts 3 parameters.
  <ol>
    <li>Name</li>
    <li>Description</li>  
    <li>Author</li>  
  </ol>
 </li>
<li>When clicked on any project you will be redirected to the project details page.</li>
<li>Project details page have following features:
  <ol>
    <li>A button to create an issue.</li>
    <li>Filter by multiple labels i.e. you will be able to filter by 2 or more labels at the same time.</li>
    <li>Filter by author.</li>
    <li>Search by title.</li>
    <li>Search by description.</li>
  </ol>
</li>
<li>Creating a issue will accept following parameters:
  <ol>
  <li>Title</li>
  <li>Description</li>
  <li>Labels : Multiple labels can be added to a project, if a project has a label already it will be shown in dropdown you will user type the label in</li>
  <li>Author</li>
  </ol>
</li>
</ol>

<h2>Prerequisites:</h2>
  <ol>
    <li>Node should be installed on your Device</li>
    <li>Mongo DB should be installed</li>
  </ol>
 
<h2>How to setup ?</h2>
  <ol>
    <li>Download the zip file for this project from the repository</li>
    <li>Extract the file open in VS Code.</li>
    <li>Run <code>npm i</code> this will install all dependencies.</li>
    <li>Run <code>nodemon index.js</code> (if this command doesn't work, then nodemon is not installed globally in your system, please run <code>npm i nodemon</code> before running this command.)</li>
    <li>The app will be live on port 8000, you can access it using url <code>http://localhost:8000</code> in your browser.</li>
    <p><strong>Note : To run in local environment and link to your local mongo data base just uncomment the line 8 and comment line 3 and 9 in <code>mongoose.js</code> as the project is linked to cloud data base.</strong></p>
  </ol>
  


