@startuml
class App {
+Stringdir:Aktienverwaltung/data/
+Fileaccounts:newfile
+Filestocks:newfile
}

class Server{

importjava.io.BufferedReader
importjava.io.BufferedWriter
importjava.io.File
importjava.io.FileNotFoundException
importjava.io.FileReader
importjava.io.FileWriter
importjava.io.IOException
importjava.net.ServerSocket
importjava.net.Socket
importjava.util.Random
importjava.util.Scanner
importcom.google.gson.Gson
importcom.google.gson.JsonSyntaxException
_______________________________________________________________________________

ServerSocket serverSockert = null
Socket socket = null
this.dir = dir 
gson = new Gson 
cmdInmput.start()
generateStockValues.start ()

____________________________________
public void run() 

Random rand = new Random()
BufferedReader reader
BufferWriter writer
Stock.addValue(stock.getValues().length, stock.getValues(), newValue)
writer = new BufferWriter(new FileWriter(file))
writer.write (gson.toJson(stock))
reader.close()
writer.close ()
Thread cmdInput = new Thread(new Runnable(),String stockName = input[2];Integer[] stockValue = {null},
Integer stockValue = null
Stock stock = new Stock (stockName, stockValue
writer = new BufferedWriter
writer.write
______________________________________


}
@enduml