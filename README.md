xml-resume
==========

An XML storage format with XSLT stylesheets for formatting

Schema validation
=================

    xmllint --noout --schema schema/resume.xsd myresume.xml

HTML generation
===============

    xsltproc xsl/html.xsl myresume.xml > myresume.html
