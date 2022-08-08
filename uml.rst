|CICD job|
start
:fetch git repo;
:use job cache;
:before script;
|general preparation|
:(un)set proxy settings;
:echo debug information;
:prepare ssh connection to CSC;
:clone git dependency;
|CICD job|
:prepare script;
|specific preparation e.g. Terraform|
:prepare ci folder & set first environment vars;
:prepare terraform variables;
:prepare tagging;
:prepare remote state;
:initiate terraform state & modules;
|CICD job|
:execute job specific tasks;
:update cache;
stop
