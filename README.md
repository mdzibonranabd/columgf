# columgf
import 'package:flutter/material.dart';
void main() => runApp (MyApp ());
class MyApp extends StatelessWidget{
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Scaffold(
          appBar: AppBar(title:   Center(child: Text(" MD Jibon Rana", style: TextStyle(fontSize: 50.0),),)),
          body: Center(
            child: GridView.count(crossAxisCount: 4,

              children: <Widget>[
               Container(
                 color: Colors.red,
                 padding: EdgeInsets.all(20.0),
                 child:Center(
                   child:  Text("My", style: TextStyle(fontSize: 20.0),),
                 ) ,
               ),

                Container(

                  color: Colors.white12,
                  child:Center(
                    child:  Text("name", style: TextStyle(fontSize: 20.0),),

                  ) ,
                ),

                Container(
                  color: Colors.redAccent,
                  child:Center(
                    child:  Text("is", style: TextStyle(fontSize: 20.0),),
                  ) ,
                ),
                Container(
                  color: Colors.blue,
                  child:Center(
                    child:  Text("jibon", style: TextStyle(fontSize: 20.0),),
                  ) ,
                ),
                Container(
                  color: Colors.orange,
                  child:Center(
                    child:  Text("rana", style: TextStyle(fontSize: 20.0),),
                  ) ,
                ),
                Container(
                  color: Colors.indigoAccent,
                  child:Center(
                    child:  Text("i", style: TextStyle(fontSize: 20.0),),
                  ) ,
                ),
                Container(
                  color: Colors.pinkAccent,
                  child:Center(
                    child:  Text("am", style: TextStyle(fontSize: 20.0),),
                  ) ,
                ),
                Container(
                  color: Colors.deepOrange,
                  child:Center(
                    child:  Text("a", style: TextStyle(fontSize: 20.0),),
                  ) ,
                ),
                Container(
                  color: Colors.deepOrange,
                  child:Center(

                    child: Text(
                    'Student',
                    style: TextStyle(fontSize: 30.0),
                    ),
                  ) ,
                ),
                Container(
                  color: Colors.blueGrey,
                  child:Center(
                    child: Text(
                      'In',
                      style: TextStyle(fontSize: 20.0),
                    ),
                  ) ,
                ),
                Container(
                  color: Colors.lime,
                  child:Center(
                    child: Text(
                      'Rajshahi',
                      style: TextStyle(fontSize: 40.0),
                    ),
                  ) ,
                ),
                Container(
                  color: Colors.cyanAccent,
                  child:Center(
                    child:  Text("polytechin", style: TextStyle(fontSize: 20.0),),
                  ) ,
                ),
                Container(
                  color: Colors.greenAccent,
                  child:Center(
                    child:  Text("Inistitute", style: TextStyle(fontSize: 20.0),),
                  ) ,
                ),
                Container(
                  color: Colors.lightGreen,
                  child:Center(
                    child:  Text("THINK TOU", style: TextStyle(fontSize: 20.0),),
                  ) ,
                ),
                Container(
                  color: Colors.amberAccent,
                  child:Center(
                    child:  Text("End", style: TextStyle(fontSize: 20.0),),
                  ) ,
                ),

              ],
            ),
          ),
      ),
    );
   }
  }
