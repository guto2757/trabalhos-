# trabalhos-
import 'package:flutter/material.dart';

void main() {
  runApp(MeuApp());
}

class MeuApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'App teste com fluter',
      home: Scaffold(
        appBar: AppBar(
          title: Text('Testando App'),
        ),
        body: Center(
          child: Text(
            'Teste executado',
            style: TextStyle(fontSize: 18),
          ),
        ),
        floatingActionButton: FloatingActionButton(
          onPressed: () {},
          child: Icon(Icons.add),
        ),
      ),
    );
  }
}
