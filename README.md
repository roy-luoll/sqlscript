# sqlscript
Generate SQL text from a defined template. It's not a general template engine, as these engines are everywhere. 
This tiny tool is a standlone , little footprint executable files and very simple grammar.

// this ia demo SQL text.
%for suffix in range(0,10):
create table region${suffix} (
  int id;
  string name;
);
%endfor

A series of table definition will be produced and DBA can use it to generate database objects!
