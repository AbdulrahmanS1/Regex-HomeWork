# HW-Regex

<div dir=rtl>
 السؤال الأول : اكتب regex تطابق lives و lived.

	 regex :  live[sd]
	 number of match : 7
  </div><div dir=rtl>
اكتب regex تطابق الكلمة virtue, لكن يجب أن لا تطابق الكلمة virtues
 
	 regex :  virtue[^s]
	 number of match : 14
  </div> <div dir=rtl>
  اكتب regex تطابق الفقرات المرقمة (.1.2.3.4.)

	 regex :  [1-4][\\.]
	 number of match : 4 
  </div><div dir=rtl>
اوجد كلمة تتكون من 16 حرف تبدأ بحرف c

	 regex :  c[a-z]{15}
	 number of match : 1 
	 The word: circumnavigation
  </div>
