MOCK TEST SYSTEM
=================

সেটিং:
- মোট প্রশ্ন: 50
- মোট নম্বর: 50
- সময়: 40 মিনিট
- সঠিক উত্তর: +1
- ভুল উত্তর: -0.25
- উত্তর না দিলে: 0

ফোল্ডার:
mock-test-01 = Mock Test 01
mock-test-02 = Mock Test 02
mock-test-03 = Mock Test 03

প্রতিটি Mock Test-এর questions.js আলাদা।
তাই Mock Test 01-এর প্রশ্ন বদলালে Mock Test 02/03 বদলাবে না।

ভবিষ্যতে Mock Test 04:
1. mock-test-03 ফোল্ডার কপি করুন।
2. নাম দিন mock-test-04।
3. mock-test-04/questions.js-এ নতুন 50 প্রশ্ন বসান।
4. TEST_CONFIG.title বদলে MOCK TEST-04 করুন।
5. GitHub-এ mock-test-04 ফোল্ডার আপলোড করুন।

প্রশ্নের ফরম্যাট:
const TEST_CONFIG = {
  title: "WBPSC MISCELLANEOUS PRELIMINARY EXAM - 2026 | FULL LENGTH MOCK TEST-01",
  durationMinutes: 40,
  marksPerCorrect: 1,
  negativePerWrong: 0.25
};

const questions = [
  {
    q: "প্রশ্ন এখানে লিখুন",
    options: ["অপশন ১","অপশন ২","অপশন ৩","অপশন ৪"],
    answer: 0
  }
];

answer-এ 0 = প্রথম অপশন, 1 = দ্বিতীয়, 2 = তৃতীয়, 3 = চতুর্থ।
