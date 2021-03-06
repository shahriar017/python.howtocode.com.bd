## ব্যাসিক অপারেশন

পাইথনের কনসোলে সহজেই ম্যাথেম্যাটিক্যাল ক্যালকুলেশন করা যায়। তাই আবার খুলে ফেলুন পাইথন ইন্টারপ্রেটার। অর্থাৎ, নিচের যেকোনো একটিঃ   

১) পাইথন ইন্সটলেশনের সাথে আশা  IDLE   
২) লিনাক্স বা ম্যাক হলে Terminal ওপেন করুন এবং টাইপ করুন python3   
৩) উইন্ডোজ হলে Command Prompt চালু করুন এবং টাইপ করুন python   

কনসোলে নিচের মত ম্যাথেম্যাটিক্যাল কমান্ড লিখে সহজেই সেগুলোর রেজাল্ট পাওয়া যায় -

```python
>>> 2 + 6
8
>>> 5 + 4 - 3
6
```

যোগ বিয়োগের মতই গুন ভাগের কাজও এখানে সহজেই করা যায়। ব্রাকেট ব্যবহার করে নির্ধারণ করে দেয়া যায় যে, কোন পার্ট টুকুর অপারেশন আগে করা হবে।

```python
>>> 2 * (2 + 2)
8
>>> 20/2
10.0
```
একটি সিঙ্গেল ```/``` ব্যবহার করে ভাগ করলে রেজাল্ট আসে ```float``` টাইপের ডেসিম্যাল।

```python
>>> -7 + 2
-5
```
নাম্বারের আগে মাইনাস সাইন দিয়ে নেগেটিভ নাম্বার নির্ধারণ করে দেয়া হয়।

সাধারণ গণিতের মতই পাইথনে কোন সংখ্যাকে শূন্য দিয়ে ভাগ করতে গেলে এরর আসবে, 

```python
>>> 44/0
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
ZeroDivisionError: division by zero
```

###Float
যে নাম্বার গুলো Integer টাইপের নয় সেগুলোকে পাইথনে রিপ্রেজেন্ট করার জন্য float ব্যবহার করা হয়। যেমন - 1.0, -5.15 ইত্যাদি। যেকোনো সংখ্যার মধ্যে একটি দশমিক চিহ্ন ব্যবহার করা মানেই হল সেটি একটি float টাইপের ডাটা হয়ে যায়। অথবা পাইথনে যেকোনো দুটি ইন্টিজার টাইপের সংখ্যাকে ভাগ করলেই একটি float টাইপের রেজাল্ট পাওয়া যায়। যেমন, 

```python
>>> 10/5
2.0
```

একটা কথা মনে রাখা জরুরি - মানুষের মত কম্পিউটারও শতভাগ সঠিকভাবে float টাইপের ডাটা স্টোর করতে পারে না। যেমন 1/3 এর ফলাফল হচ্ছে 0.333333333 (চলতেই থাকে)। এরকম অবস্থা কিছু অনাকাঙ্ক্ষিত ত্রুটির কারণ হয়ে দাঁড়াতে পারে। 

```python
>>> 8 / 2
4.0
>>> 6 * 7.0
42.0
>>> 4 + 1.65
5.65
```



