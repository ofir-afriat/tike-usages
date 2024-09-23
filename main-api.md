get full meta data of file: 

`curl -T test.pdf http://localhost:9998/meta` 
output 

`
➜  Downloads curl -T e.docx http://localhost:9998/meta
cp:revision,2
extended-properties:AppVersion,16.0000
meta:paragraph-count,52
meta:word-count,3925
custom:MSIP_Label_9386b39a-f873-4afb-95b7-159453b5f857_Method,Standard
custom:MSIP_Label_9386b39a-f873-4afb-95b7-159453b5f857_ContentBits,0
X-TIKA:Parsed-By-Full-Set,org.apache.tika.parser.DefaultParser,org.apache.tika.parser.microsoft.ooxml.OOXMLParser
dc:creator,raz.i
extended-properties:Company,Ofir
meta:print-date,2012-03-12T08:22:00Z
dcterms:created,2024-09-09T04:46:00Z
meta:line-count,186
language,he
dcterms:modified,2024-09-09T04:46:00Z
meta:character-count,22374
meta:character-count-with-spaces,26247
dc:title,my-title
extended-properties:TotalTime,2
Content-Length,746699
Content-Type,application/vnd.openxmlformats-officedocument.wordprocessingml.document
extended-properties:Application,Microsoft Office Word
meta:last-author,Ofir
xmpTPg:NPages,27
custom:MSIP_Label_9386b39a-f873-4afb-95b7-159453b5f857_SiteId,3d918542-68a9-4e89-ac7a-0f74754ddb24
extended-properties:Template,Normal
X-TIKA:Parsed-By,org.apache.tika.parser.DefaultParser,org.apache.tika.parser.microsoft.ooxml.OOXMLParser
extended-properties:DocSecurityString,None
meta:page-count,27
dc:publisher
`
