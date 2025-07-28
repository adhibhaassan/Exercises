# CHECK-IN PROJECT
> DATA CLASSES

**1.Employee**
  - id :Int
  - firstName :String 
  - lastName :String
  - role :String
  - contactNumber :String
    
**2.EmployeeCheckIn**
  - id :Int
  - date :LocalDate
  - time :LocalTime

> FUNCTIONS

**1.addEmployee()**
  - gets firstName,lastName,role and contactNumber from user and creates an id automatically.
  - stores in  employeeDetails(Map) using Employee data class

**2.validateId()**
  - checks whether id is present in employeeDetails map

**3.hasCheckedInToday()**
  - checks whether id is present in checkedInDetails map

**4.createCheckIn()**
  - gets user id and takes local date and local time and validates id using validateId() and hasCheckedInToday()
  - stores data in checkedInDetails map using CheckIn(Data class)

> MAP

**1.employeeDetails**
employeeDetails={
  id:{
    firstName:"    ",
    lastName:"     ",
    role:"         ",
    contactNumber:"     "
  }
}

**2.checkedInDetails**
checkedInDetails={
  date:{
    id1:"time",
    id2:"time",
    .
    .
  }
}
