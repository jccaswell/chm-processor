UdfAttribute Class   
[Members](topic7257.md)   
[DriveWorks.Engine Assembly](topic2156.md) > [DriveWorks.Extensibility Namespace](topic7150.md) : UdfAttribute Class  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

Glossary Item Box

Designates a method on a [ProjectExtender](topic7232.md) or a [SharedProjectExtender](topic7248.md) as a user defined function to be available in a design master. 

# Object Model

![](dotnetdiagramimages/image393.png)

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    <AttributeUsageAttribute(ValidOn=AttributeTargets.Method, 
       AllowMultiple=False, 
       Inherited=True)>
    Public Class UdfAttribute 
       Inherits System.Attribute  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [UdfAttribute](topic7256.md)  
  
C#|   
---|---  
      
    
    [AttributeUsageAttribute(ValidOn=AttributeTargets.Method, 
       AllowMultiple=false, 
       Inherited=true)]
    public class UdfAttribute : System.Attribute   
  
# Inheritance Hierarchy

System.Object  
System.Attribute  
**DriveWorks.Extensibility.UdfAttribute**  


# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[UdfAttribute Members](topic7257.md)   
[DriveWorks.Extensibility Namespace](topic7150.md)


