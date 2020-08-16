import 'package:flutter/cupertino.dart';
import 'package:flutter/material.dart';
import 'package:url_launcher/url_launcher.dart';
import 'package:font_awesome_flutter/font_awesome_flutter.dart';
import 'package:carousel_slider/carousel_slider.dart';
void main() {
  runApp(MaterialApp(
    home:Home(),
  ));
}

class Home extends StatefulWidget {
  @override
  _HomeState createState() => _HomeState();
}

class _HomeState extends State<Home> {
  _linkedinURL(String $link_id) async
  {
    var url='https://linkedin.com/in/'+$link_id;
    if(await canLaunch(url))
      await launch(url);
    else
      throw 'Could noy launch $url';
  }

  @override
  Widget build(BuildContext context) {
    return SafeArea(
      bottom: false,
      child: Scaffold(
        resizeToAvoidBottomInset: true,
        backgroundColor: Colors.grey[800],
          appBar:AppBar(
            title: Text('DEVELOPERS',
                style: TextStyle(
                fontWeight: FontWeight.bold,
            ),
            ),
            centerTitle: true,
            backgroundColor: Colors.grey[900],
          ),
          body:SingleChildScrollView(
            child: Container(
              child: Column(
                mainAxisAlignment: MainAxisAlignment.center,
                crossAxisAlignment: CrossAxisAlignment.center,
                children: <Widget>[
                  CarouselSlider(
                    options:CarouselOptions(
                      height: 610,
                      initialPage: 0,
                      aspectRatio: 2.0,
                      enableInfiniteScroll: false,
                      autoPlay: false,
                      scrollDirection: Axis.vertical,
                      enlargeCenterPage: true,
                    ) ,
                    items: <Widget>[
                      Padding(      //Abhilaksh Kaushik*************
                        padding: const EdgeInsets.fromLTRB(50,30,50,30),
                        child: Container(
                            //height: 600,
                           child: Material(
                            elevation: 10,
                            borderRadius: BorderRadius.circular(20.0),
                            shadowColor: Colors.black87,
                            color: Colors.grey[900],
                            child:Column(
                              children: <Widget>[
                                SizedBox(height: 10),
                                CircleAvatar(
                                  backgroundImage:AssetImage('assets/download.jpg'),
                                  radius:100,
                                ),
                                SizedBox(height: 10),
                                Text(
                                  'NAME: \nAbhilaksh Kaushik'
                                  '\n\nSKILLS: \nSwift,SwiftUI,CCNA,CCNP'
                                  '\n\nWORKING in:\nVVDN Technologies',
                                  style: TextStyle(
                                    color: Colors.white,
                                  ),
                                ),
                                /*Text(
                                  'LEVEL 1',
                                  style: TextStyle(
                                    color: Colors.white,
                                  ),
                                ),*/
                                SizedBox(height: 20),
                                RaisedButton.icon(
                                  onPressed: ()
                                  {_linkedinURL('abhilaksh-kaushik-57502717a');},
                                  icon: Icon(FontAwesomeIcons.linkedin),
                                  label:Text('LinkedIn Profile'),
                                  color: Colors.amber,
                                ),
                              ],
                            ),
                          ),
                        ),
                      ),
                      Padding(
                        padding: const EdgeInsets.fromLTRB(50,20,50,30),
                        child: Container(
                          child: Material(
                            elevation: 10,
                            borderRadius: BorderRadius.circular(20.0),
                            shadowColor: Colors.black87,
                            color: Colors.grey[900],
                            child:Column(
                              children: <Widget>[
                                SizedBox(height: 10),
                                CircleAvatar(
                                  backgroundImage:AssetImage('assets/nezuko.jpg'),
                                  radius:100,
                                ),
                                SizedBox(height: 10),
                                Text(
                                  'NAME:\nRuchi Chawla '
                                      '\n\nPre Final Year                   '
                                      '\n\nSKILLS:\nC,C++',
                                  style: TextStyle(
                                    color: Colors.white,
                                  ),
                                ),
                                SizedBox(height: 30),
                                RaisedButton.icon(
                                  onPressed: ()
                                  {_linkedinURL('ruchi-chawla-4978911a1');},
                                  icon: Icon(FontAwesomeIcons.linkedin),
                                  label:Text('LinkedIn Profile'),
                                ),
                              ],
                            ),
                          ),
                        ),
                      ),
                      Padding(//Nilansh Verma******************
                        padding: const EdgeInsets.fromLTRB(50,20,50,30),
                        child: Container(
                          child: Material(
                            elevation: 10,
                            borderRadius: BorderRadius.circular(20.0),
                            shadowColor: Colors.black87,
                            color: Colors.grey[900],
                            child:Column(
                              children: <Widget>[
                                SizedBox(height: 10),
                                CircleAvatar(
                                  backgroundImage:AssetImage('assets/download.jpg'),
                                  radius:100,
                                ),
                                SizedBox(height: 10),
                                Text(
                                  'NAME:\nNilansh Verma'
                                      '\n\nPre Final Year'
                                      '\n\nSKILLS:\nWeb Development,Cyber Security',
                                  style: TextStyle(
                                    color: Colors.white,
                                  ),
                                ),
                                SizedBox(height: 30),
                                RaisedButton.icon(
                                  onPressed: ()
                                  {_linkedinURL('nilansh-verma-0b93261a6');},
                                  icon: Icon(FontAwesomeIcons.linkedin),
                                  label:Text('LinkedIn Profile'),
                                ),
                              ],
                            ),
                          ),
                        ),
                      ),

                      Padding(//Aman Singh******************
                        padding: const EdgeInsets.fromLTRB(50,20,50,30),
                        child: Container(
                          child: Material(
                            elevation: 10,
                            borderRadius: BorderRadius.circular(20.0),
                            shadowColor: Colors.black87,
                            color: Colors.grey[900],
                            child:Column(
                              children: <Widget>[
                                SizedBox(height: 10),
                                CircleAvatar(
                                  backgroundImage:AssetImage('assets/download.jpg'),
                                  radius:100,
                                ),
                                SizedBox(height: 10),
                                Text(
                                  'NAME:\nAman Singh                       '
                                      '\n\n2nd Year'
                                      '\n\nSKILLS:\nC,C++',
                                  style: TextStyle(
                                    color: Colors.white,
                                  ),
                                ),
                                SizedBox(height: 30),
                                RaisedButton.icon(
                                  onPressed: ()
                                  {_linkedinURL('aman-singh-8a5892191');},
                                  icon: Icon(FontAwesomeIcons.linkedin),
                                  label:Text('LinkedIn Profile'),
                                ),
                              ],
                            ),
                          ),
                        ),
                      ),
                      //SizedBox(height: 20,),
                    ],
                  ),
                ],
              ),
            ),
          )
          /*ListView(
            //: Axis.horizontal,
            children:<Widget>[
              Padding(
                padding: const EdgeInsets.fromLTRB(50, 30,50,20),
                child: Container(
                 // padding: EdgeInsets.all(20),
                 // margin: EdgeInsets.all(20),
                  child: Material(
                    elevation: 10,
                    borderRadius: BorderRadius.circular(20.0),
                    shadowColor: Colors.black87,
                    color: Colors.grey[900],
                    child:Column(
                      crossAxisAlignment: CrossAxisAlignment.center,
                      children: <Widget>[
                        SizedBox(height: 10),
                        CircleAvatar(
                              backgroundImage:AssetImage('assets/download.jpg'),
                                radius:100,
                        ),
                        SizedBox(height: 10),
                        Text(
                            'Tangiro',
                            style: TextStyle(
                              color: Colors.white,
                            ),
                        ),
                        Text(
                            'LEVEL 1',
                            style: TextStyle(
                              color: Colors.white,
                            ),
                        ),
                        SizedBox(height: 30),
                        RaisedButton.icon(
                            onPressed: ()
                            {_linkedinURL('aman-singh-8a5892191');},
                            icon: Icon(FontAwesomeIcons.linkedin),
                            label:Text('LinkedIn Profile'),
                        ),
                        ],
                    ),
                  ),
                ),
              ),
              Padding(
                padding: const EdgeInsets.fromLTRB(50, 30,50,20),
                child: Container(
                  child: Material(
                    elevation: 10,
                    borderRadius: BorderRadius.circular(20.0),
                    shadowColor: Colors.black87,
                    color: Colors.grey[900],
                    child:Column(
                      crossAxisAlignment: CrossAxisAlignment.center,
                      children: <Widget>[
                        SizedBox(height: 10),
                        CircleAvatar(
                          backgroundImage:AssetImage('assets/download.jpg'),
                          radius:100,
                        ),
                        SizedBox(height: 10),
                        Text(
                          'Tangiro',
                          style: TextStyle(
                            color: Colors.white,
                          ),
                        ),
                        Text(
                          'LEVEL 1',
                          style: TextStyle(
                            color: Colors.white,
                          ),
                        ),
                        SizedBox(height: 30),
                        RaisedButton.icon(
                          onPressed: ()
                          {_linkedinURL('aman-singh-8a5892191');},
                          icon: Icon(FontAwesomeIcons.linkedin),
                          label:Text('LinkedIn Profile'),
                        ),
                      ],
                    ),
                  ),
                ),
              ),

            ],
          )*/
      ),
    );
  }
}
