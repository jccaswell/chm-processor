Collapse All Expand All Language Filter: All  Language Filter: Multiple  Language Filter: Visual Basic (Declaration) Language Filter: Visual Basic (Usage) Language Filter: C#  
---  
DriveWorks SDK Documentation  |   
---|---  
GetCreationWizard Method   
  
[DriveWorks.Applications Assembly](topic13.md) > [DriveWorks.Applications.Administrator.Extensibility.DataTables Namespace](topic1432.md) > [IDataTableDesigner Interface](topic1434.md) : GetCreationWizard Method  
---  
  
Visual Basic (Declaration)    
Visual Basic (Usage)    
C# 

_application_
    The running application.

Glossary Item Box

Gets a wizard used to configure a new data table of the supported type. 

# Syntax

Visual Basic (Declaration)|   
---|---  
      
    
    Function GetCreationWizard( _
       ByVal _application_ As [IApplication](topic24.md) _
    ) As [IWizard](topic613.md)  
  
Visual Basic (Usage)| Copy Code  
---|---  
      
    
    Dim instance As [IDataTableDesigner](topic1434.md)
    Dim application As [IApplication](topic24.md)
    Dim value As [IWizard](topic613.md)
     
    value = instance.GetCreationWizard(application)  
  
C#|   
---|---  
      
    
    [IWizard](topic613.md) GetCreationWizard( 
       [IApplication](topic24.md) _application_
    )  
  
#### Parameters

 _application_
    The running application.

# Remarks

The wizard must not actually create the data table, it can only gather information from the user which will be used to create the data table.

The data table will be created by the application, and passed along with the wizard to the [InitializeNewDataTable](topic1442.md) method as soon as the wizard completes.

If a null reference (Nothing in Visual Basic) is returned, then no further wizard will be shown but the [InitializeNewDataTable](topic1442.md) method will still be called in case the designer needs to perform any basic initialization.

# Requirements

**Target Platforms:** Please see DriveWorks software prerequisites.

# See Also

#### Reference

[IDataTableDesigner Interface](topic1434.md)   
[IDataTableDesigner Members](topic1435.md)


