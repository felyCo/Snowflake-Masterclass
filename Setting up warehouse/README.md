# Setting up warehouse


This can be done in two ways namely;
- SQL Commands
- Interface

Using the Interface it happens as follows;
 Go to Admin >> Warehouse (You will see all the avaialble warehouses) Then to create a new warehouse click the >> + Warehouses
 >> Provide Name the Size(Credits/hour)   >> Providing a Description is ideal
 >> Query Acceleration(For large table scan and optimization and dynamic acceleration feel free to enable this however this will increase the cost (Enable/Otherwise)
 >> Multi-cluster Warehouse  (Reccomended for larger companies this is enable to increase the computing power in a dynamic manner)- For example if the data input is expected to peak at certain period of time, the computing powe dynamically increases at that time. This option is eanbled by default.
 >> - Mode  {Auto-scale}
 >> - Min Clusters {#}
 >> - Max Clusters {#}
 >> - Scaling Policy {Standard}/{Economy}

>> Advanced Warehouse Options >> This is an option where no changes need to be made but at some point a consideration could suffice.
>> - Auto Resume { Automatically resuming warehouse operation after suspension}
>> - Auto Suspend { Automatically suspends a warehouse operation when not in use}
>> Warehouse Type {Standard} or {Snowpark-optimized} >> Reccomended for some machine learning or compute intensive query
>> 


