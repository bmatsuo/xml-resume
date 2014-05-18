xml-resume
==========

An XML vocabulary with XSLT stylesheets for formatting

Validate
========

    xmllint --noout --schema schema/resume.xsd myresume.xml

Generate HTML
=============

    xsltproc xsl/html.xsl myresume.xml > myresume.html
