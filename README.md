# megabytesconverter
# Challenge from Tim Buchalka's Java Programming Masterclass for Software Developers course

Write a method called printMegaBytesAndKiloBytes that has 1 parameter of type int with the
name kiloBytes.

The method should not return anything (void) and it needs to calculate the megabytes and
remaining kilbytes from the kilbytes parameter.

Then it needs to print a message in the format "XX KB = YY MB and ZZ KB".

XX represents the origianl value kiloBytes
YY represents the calculated megabytes.
ZZ represents the calculated remaining kilobytes.

For example, when the parameter kiloBytes in 2500 it needs to print "2500 KB = 2 MB and 452
KB"

If the parameter kilBites is less than 0 then print the text "Invalid Value".

EXAMPLE INPUT/OUTPUT
    * printMegaBytesAndKiloBytes(2500); -> should print the following text: "2500 KB = 2 
      MB and 452 KB"
      
    * printMegaBytesAndKiloBytes(-1024); -> should print the following text: "Invalid 
        Value" because parameter is less than 0.
      
    * printMegaBytesAndKiloBytes(5000); -> should print the following text: "5000 KB = 4
      MB and 904 KB"
      
TIP: Be extremely careful about spaces in the printed message.
TIP: Use the remainder operator
TIP: 1 MB = 1024 KB

NOTE: Do not set kilobytes parameter value inside your method.
NOTE: The solution will not be accepted if there are extra spaces.
NOTE: The printMegaBytesAndKiloBytes method needs to be defined as public static
NOTE: Do not add a main method to solution code.

    
