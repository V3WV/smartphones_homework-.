import 'package:flutter/material.dart';

void main() {
  runApp(const MyFirstAssignment());
}

class MyFirstAssignment extends StatelessWidget {
  const MyFirstAssignment({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      debugShowCheckedModeBanner: false, // لإخفاء شريط التصحيح المزعج
      home: Scaffold(
        appBar: AppBar(
          title: const Text('الواجب الأول'),
          centerTitle: true,
          backgroundColor: Colors.blueAccent,
        ),
        body: Center(
          child: Column(
            mainAxisAlignment: MainAxisAlignment
                .center, // لتوسيط العناصر عمودياً داخل الـ Column
            children: const [
              Text(
                'الاسم:عبدالله حمود الاحمري',
                style: TextStyle(fontSize: 24, fontWeight: FontWeight.bold),
              ),
              SizedBox(height: 10), // مسافة بسيطة بين النصين
              Text(
                'الرقم الأكاديمي: 444227318',
                style: TextStyle(fontSize: 20, color: Colors.grey),
              ),
            ],
          ),
        ),
      ),
    );
  }
}
