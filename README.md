dotnet new webapi -n PlatformService

code -r PlatformService

dotnet add package AutoMapper.Extensions.Microsoft.DependencyInjection

dotnet add package Microsoft.EntityFrameworkCore

dotnet add package Microsoft.EntityFrameworkCore.Design

dotnet add package Microsoft.EntityFrameworkCore.InMemory

dotnet add package Microsoft.EntityFrameworkCore.SqlServer

prop+TAB CTRL+. CTOR+TAB

after List is a placeholder<T>,because not know its type,but when used we can give it the type name.it is custom type in <>.
  
  (
  
  Student stu1 = new Student("1001","tom“，18，”101class");
  
  List<Student> stuList=new List<Student>();//mandatory type - ArrayList studentList = new ArrayList();
  
  stuList.Add(stu1);//stuList.Add(new Student("1001","tom“，18，”101class"));
  
  )
  
  dotnet build
  
  dotnet run
  
 
