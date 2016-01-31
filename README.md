## Description
The SetEmailAttachmentFilename pipeline component sets the outgoing message BodyPart MIME FileName property to the value of a context property of the processed message.  

## SetEmailAttachmentFilename
SetEmailAttachmentFilename consists of a pipeline used to set the MIME FileName BodyPart property.

## Parameters
PropertyPath

Should be in the format of namespace#propertyname. Example:
http://testnamespace.com#testpropertyname

The pipeline will assign the MIME FileName property of the outgoing message to the value of the context property with the same namespace#property as the PropertyPath parameter
