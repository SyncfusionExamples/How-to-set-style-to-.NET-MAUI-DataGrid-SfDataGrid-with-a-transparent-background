# How to set style to .NET MAUI DataGrid SfDataGrid with a transparent background
The [SfDataGrid](https://www.syncfusion.com/maui-controls/maui-datagrid) allow you to customize its background color by setting the `BackgroundColor` property to Transparent.

##### xaml:
 ```XML
 <StackLayout BackgroundColor="LightBlue">
    <syncfusion:SfDataGrid  ItemsSource="{Binding Employees}"
                            BackgroundColor="Transparent"
                            DefaultColumnWidth="155"
                            VerticalOptions="FillAndExpand"
                            AutoGenerateColumnsMode="None">
        <syncfusion:SfDataGrid.Columns>
            <syncfusion:DataGridTextColumn MappingName="EmployeeID"
                                           HeaderText="Employee ID" />
            <syncfusion:DataGridTextColumn MappingName="Name"
                                           HeaderText="Name" />
            <syncfusion:DataGridTextColumn MappingName="IDNumber"
                                           HeaderText="ID Number" />
        </syncfusion:SfDataGrid.Columns>

    </syncfusion:SfDataGrid>
</StackLayout>
 ```
 

Executing the code example above yields the following output.

<img src="backgroundColor.png" width="360">

[View sample in GitHub](https://github.com/SyncfusionExamples/How-to-set-style-to-.NET-MAUI-DataGrid-SfDataGrid-with-a-transparent-background/tree/master)

Take a moment to explore this [documentation](https://help.syncfusion.com/maui/datagrid/overview), where you can find more information about Syncfusion .NET MAUI DataGrid (SfDataGrid) with code examples. Please refer to this [link](https://www.syncfusion.com/maui-controls/maui-datagrid) to learn about the essential features of Syncfusion .NET MAUI DataGrid (SfDataGrid).

##### Conclusion

I hope you enjoyed learning about how to set style to .NET MAUI DataGrid (SfDataGrid) with a transparent background.

You can refer to our [.NET MAUI DataGrid’s feature tour](https://www.syncfusion.com/maui-controls/maui-datagrid) page to learn about its other groundbreaking feature representations. You can also explore our [.NET MAUI DataGrid Documentation](https://help.syncfusion.com/maui/datagrid/getting-started) to understand how to present and manipulate data. 
For current customers, you can check out our .NET MAUI components on the [License and Downloads](https://www.syncfusion.com/sales/teamlicense) page. If you are new to Syncfusion, you can try our 30-day [free trial](https://www.syncfusion.com/downloads/maui) to explore our .NET MAUI DataGrid and other .NET MAUI components. 

If you have any queries or require clarifications, please let us know in the comments below. You can also contact us through our [support forums](https://www.syncfusion.com/forums), [Direct-Trac](https://support.syncfusion.com/create) or [feedback portal](https://www.syncfusion.com/feedback/maui?control=sfdatagrid), or the feedback portal. We are always happy to assist you!
