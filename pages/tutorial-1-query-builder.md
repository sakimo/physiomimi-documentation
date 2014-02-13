## Tutorial 1 - Query Builder

Go to Physio-MIMI website https://mimi.case.edu<sup>[Fig01]</sup>. Sign in if you already have an account registered, otherwise please Sign Up to request access (red box).

<div class="panel panel-default">
  <div class="panel-body">
  <a href=":images_path:/tutorial/physiomimi-01-login.png?inline=1">
    <img src=":images_path:/tutorial/physiomimi-01-login.png">
  </a>
  </div>
  <div class="panel-footer">
    <h3 class="panel-title">Fig01: The Physio-MIMI website login page.</h3>
  </div>
</div>

After you successfully login, you will see the **Query Builder** page<sup>[Fig02]</sup>.
<ul>
  <li>In the "Area for data source selection" (red box 1), you can select data sources of interest (e.g., <a href=":datasets_path:/shhs">Sleep Heart Health Study</a> (SHHS for short)).</li>
  
  <li>In the "Area for searching variable term" (red box 2), you can search for a specific variable term like "ahi" in the text box. Then a list of candidate variable terms, which partially match the search term, are automatically displayed.</li>
  <li>Clicking an appropriate candidate term (red arrow) will add a corresponding individual query widget to the "Area for query composition" (red box 3), where you can specify the query based on the "shhs1" table only or both tables "shhs1" and "shhs2" using checkboxes.</li>
  <li>In the "Area for grouping query widgets" (red box 4), you can logically group query widgets by flipping the Boolean connectors, such as ANDs and ORs.</li>
  <li>Clicking the "Query" button on the bottom right corner of the "Area for query composition" will generate the number of unique patients satisfying the composed query criteria.</li>
</ul>

<div class="panel panel-default">
  <div class="panel-body">
  <a href=":images_path:/tutorial/physiomimi-02-querybuilder.png?inline=1">
    <img src=":images_path:/tutorial/physiomimi-02-querybuilder.png">
  </a>
  </div>
  <div class="panel-footer">
    <h3 class="panel-title">Fig02: The Query Builder interface. This shows a sample query specification for unique number of subjects in SHHS1 with Age between 45 and 60, Gender as female, Obstructive Apnea Hypopnea Index (OAHI) at 4% desat between 30 and 40.</h3>
  </div>
</div>

While you are exploring or done with the query composition, you can also scroll down and save constructed query<sup>[Fig03]</sup>. Clicking the "Save Query" button will lead you to the [Query Manager](:pages_path:/tutorial-2-query-manager.md) page, where you can manage the saved queries. 

<div class="panel panel-default">
  <div class="panel-body">
  <a href=":images_path:/tutorial/physiomimi-03-savequery.png?inline=1">
    <img src=":images_path:/tutorial/physiomimi-03-savequery.png">
  </a>
  </div>
  <div class="panel-footer">
    <h3 class="panel-title">Fig03: The Save Query Widget.</h3>
  </div>
</div>

<hr class="soften" style="margin-top: 20px;margin-bottom: 20px;"/>

<div class="center">
  <div class="btn-group">
    <a href=":pages_path:/README.md" class="btn btn-default">
      <span class="glyphicon glyphicon-chevron-up"></span>
      Physio-MIMI Overview
    </a>
    <a href=":pages_path:/tutorial-2-query-manager.md" class="btn btn-success">
      Tutorial 2 - Query Manager
      <span class="glyphicon glyphicon-chevron-right"></span>
    </a>
  </div>
</div>