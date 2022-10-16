# Warehouse-Management

- Specification
+ Have a CRUD
+ Design Object
- Object: Id, Name, IdUnit, IdSuplier, QRCode, BarCode
- Object Unit: Id, Name
- Object Suplier: Id, Name, Address, Phone, Email, MoreInfo, ContractDate
- Object Customer: Id, Name, Address, Phone, Email, MoreInfo, ContractDate
- O Input: Id, Date Input
- O InputInfo: Id, IdOject, IdInput, Count, InputPrice, OutputPrice, Status
- O Output: Id, DateOutput
- OutputInfo: Id, IdObject, IdInputInfo, Count, IdCustomer, DateOuput, Status
- Report view update every time table changed