# metadata-file-upload-type
If you're using the FLOW File Upload mechanism through Boomi INTEGRATE, it can handle custom data responses (e.g. return the contents of an uploaded spreadsheet to the flow, as a list value, from the INTEGRATE process). The implication is you need to create the type on the FLOW side to be able to handle that data (even if not customized).  This may be automated in the near future, but in the meantime you can create the type by POSTing the following metadata to the flow types endpoint:
*api/draw/1/element/type  
from inside the tooling.
