# ZKONSKYPR_XML

Output and create/download XML file in ABAP.

1. First you need to create a Structure and then a Table Type for the data that will be exported.
2. Using t-code XSLT_TOOL and then (ctrl+shift+f11), create the structure of the XML, with the Table Type from step 1.
3. Run the code with your transformation.
ex. 
CALL TRANSFORMATION zxml_transformation -> Created through XSLT_TOOL
  SOURCE sbook_table = it_sbooks -> The root directory from XSLT_TOOL
  RESULT XML praveen_xml.
