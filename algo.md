/*
 * 50 JavaScript Alqoritm Tapşırıqları - Sadədən Mürəkkəbə
 */

// ===== SƏVİYYƏ 1: SADƏ ALQORİTMLƏR =====

/*
 * --------------Tapşırıq 1------------:   Massivdəki bütün ədədlərin cəmini tapın
 * 
 * Təsvir: Sizə verilmiş massivin içərisindəki bütün ədədləri toplayıb
 * onların cəmini qaytarmalısınız.
 * 
 * Giriş: Ədədlər massivi. Məsələn: [1, 2, 3, 4, 5]
 * Çıxış: Bütün ədədlərin cəmi. Yuxarıdakı nümunə üçün: 15
 * 
 * İstifadə nümunəsi:
 * sumArray([1, 2, 3, 4, 5]); // 15
 * sumArray([-1, -2, 10]); // 7
 */
function sumArray(arr) {
  // Həlliniz
}

/*
 * --------------Tapşırıq 2------------:   Massivdəki ən böyük ədədi tapın
 * 
 * Təsvir: Verilmiş massivdə olan ən böyük ədədi tapıb qaytarmalısınız.
 * Massiv boş olmayacaq və ən azı bir element olacaq.
 * 
 * Giriş: Ədədlər massivi. Məsələn: [10, 5, 20, 8, 15]
 * Çıxış: Massivdəki ən böyük ədəd. Yuxarıdakı nümunə üçün: 20
 * 
 * İstifadə nümunəsi:
 * findLargest([10, 5, 20, 8, 15]); // 20
 * findLargest([42]); // 42
 * findLargest([-5, -10, -3]); // -3
 */
function findLargest(arr) {
  // Həlliniz
}

/*
 * --------------Tapşırıq 3------------:   Mətni tərsinə çevirmək
 * 
 * Təsvir: Verilmiş mətni tərsinə çevirib qaytarmalısınız.
 * Məsələn, "Salam" mətni "malaS" kimi qaytarılmalıdır.
 * 
 * Giriş: Mətn. Məsələn: "JavaScript"
 * Çıxış: Tərsinə çevrilmiş mətn. Yuxarıdakı nümunə üçün: "tpircSavaJ"
 * 
 * İstifadə nümunəsi:
 * reverseString("Salam"); // "malaS"
 * reverseString("123"); // "321"
 * reverseString("a"); // "a"
 */
function reverseString(str) {
  // Həlliniz
}

/*
 * --------------Tapşırıq 4------------:   Ədədin cüt və ya tək olduğunu yoxlayın
 * 
 * Təsvir: Verilmiş ədədin cüt və ya tək olduğunu təyin edin.
 * Ədəd qalıqsız 2-yə bölünürsə, cütdür, əks halda təkdir.
 * 
 * Giriş: Tam ədəd. Məsələn: 6
 * Çıxış: "Cüt" və ya "Tək" sözü. Yuxarıdakı nümunə üçün: "Cüt"
 * 
 * İstifadə nümunəsi:
 * evenOrOdd(6); // "Cüt"
 * evenOrOdd(15); // "Tək"
 * evenOrOdd(0); // "Cüt"
 */
function evenOrOdd(num) {
  // Həlliniz
}

/*
 * --------------Tapşırıq 5------------:   Mətndəki saitlərin sayını hesablayın
 * 
 * Təsvir: Verilmiş mətndə olan saitlərin (a, e, i, o, u) sayını hesablayın.
 * Yalnız ingilis əlifbasındakı saitlər nəzərə alınır və həm böyük, həm də 
 * kiçik hərflər sayılmalıdır.
 * 
 * Giriş: Mətn. Məsələn: "Hello World"
 * Çıxış: Saitlərin sayı. Yuxarıdakı nümunə üçün: 3 (e, o, o)
 * 
 * İstifadə nümunəsi:
 * countVowels("Hello"); // 2
 * countVowels("JavaScript"); // 3
 * countVowels("AEIOU"); // 5
 */
function countVowels(str) {
  // Həlliniz
}

/*
 * --------------Tapşırıq 6------------:   Ədədin faktorialını hesablayın
 * 
 * Təsvir: Verilmiş n ədədinin faktorialını hesablayın.
 * n! = n × (n-1) × (n-2) × ... × 3 × 2 × 1
 * Qeyd: 0! = 1 qəbul edilir.
 * 
 * Giriş: Müsbət tam ədəd və ya 0. Məsələn: 5
 * Çıxış: Ədədin faktorialı. Yuxarıdakı nümunə üçün: 120 (5 × 4 × 3 × 2 × 1)
 * 
 * İstifadə nümunəsi:
 * factorial(5); // 120
 * factorial(0); // 1
 * factorial(1); // 1
 */
function factorial(n) {
  // Həlliniz
}

/*
 * --------------Tapşırıq 7------------:   Mətinin palindrom olub-olmadığını yoxlayın
 * 
 * Təsvir: Verilmiş mətinin palindrom olub-olmadığını yoxlayın.
 * Palindrom - sözü həm əvvəldən, həm də sondan oxuduqda eyni olan mətndir.
 * Böyük/kiçik hərflər fərqi nəzərə alınmamalı və boşluqlar, durğu işarələri
 * yoxlamadan çıxarılmalıdır.
 * 
 * Giriş: Mətn. Məsələn: "A man, a plan, a canal: Panama"
 * Çıxış: true və ya false. Yuxarıdakı nümunə üçün: true
 * 
 * İstifadə nümunəsi:
 * isPalindrome("radar"); // true
 * isPalindrome("Radar"); // true
 * isPalindrome("hello"); // false
 */
function isPalindrome(str) {
  // Həlliniz
}

/*
 * --------------Tapşırıq 8------------:   Massivdəki ən kiçik ədədi tapın
 * 
 * Təsvir: Verilmiş ədədlər massivindəki ən kiçik ədədi tapın.
 * Massiv boş olmayacaq və ən azı bir element olacaq.
 * 
 * Giriş: Ədədlər massivi. Məsələn: [10, 5, 8, 3, 15]
 * Çıxış: Massivdəki ən kiçik ədəd. Yuxarıdakı nümunə üçün: 3
 * 
 * İstifadə nümunəsi:
 * findSmallest([10, 5, 8, 3, 15]); // 3
 * findSmallest([42]); // 42
 * findSmallest([-5, -10, -3]); // -10
 */
function findSmallest(arr) {
  // Həlliniz
}

/*
 * --------------Tapşırıq 9------------:   Mətndə bir hərfin neçə dəfə təkrarlandığını sayın
 * 
 * Təsvir: Verilmiş mətndə müəyyən bir hərfin neçə dəfə təkrarlandığını sayın.
 * Böyük və kiçik hərflər arasındakı fərqi nəzərə almayın.
 * 
 * Giriş: Mətn və bir hərf. Məsələn: "Programming", "m"
 * Çıxış: Hərfin təkrarlanma sayı. Yuxarıdakı nümunə üçün: 2
 * 
 * İstifadə nümunəsi:
 * countChar("Programming", "m"); // 2
 * countChar("JavaScript", "a"); // 2
 * countChar("Hello", "z"); // 0
 */
function countChar(str, char) {
  // Həlliniz
}

/*
 * --------------Tapşırıq 1------------0  : Selsi dərəcəsini Fahrenheytə çevirin
 * 
 * Təsvir: Verilmiş Selsi dərəcəsini Fahrenheytə çevirin.
 * Çevirmə düsturu: F = (C × 9/5) + 32
 * 
 * Giriş: Selsi dərəcəsi (rəqəm). Məsələn: 25
 * Çıxış: Fahrenheyt dərəcəsi. Yuxarıdakı nümunə üçün: 77
 * 
 * İstifadə nümunəsi:
 * celsiusToFahrenheit(25); // 77
 * celsiusToFahrenheit(0); // 32
 * celsiusToFahrenheit(-40); // -40
 */
function celsiusToFahrenheit(celsius) {
  // Həlliniz
}

// ===== SƏVİYYƏ 2: ORTA ALQORİTMLƏR =====

/*
 * --------------Tapşırıq 1------------1  : FizzBuzz
 * 
 * Təsvir: 1-dən n-ə qədər olan ədədləri emal edən FizzBuzz alqoritmini yazın:
 * - Əgər ədəd 3-ə bölünürsə, "Fizz" qaytarın
 * - Əgər ədəd 5-ə bölünürsə, "Buzz" qaytarın
 * - Əgər ədəd həm 3-ə, həm də 5-ə bölünürsə, "FizzBuzz" qaytarın
 * - Heç birinə bölünmürsə, ədədin özünü qaytarın
 * 
 * Giriş: n ədədi (tam müsbət). Məsələn: 15
 * Çıxış: 1-dən n-ə qədər olan ədədləri emal edərək alınan nəticələrdən
 * ibarət massiv.
 * 
 * İstifadə nümunəsi:
 * fizzBuzz(15); 
 * // Nəticə: [1, 2, "Fizz", 4, "Buzz", "Fizz", 7, 8, "Fizz", "Buzz", 11, "Fizz", 13, 14, "FizzBuzz"]
 */
function fizzBuzz(n) {
  // Həlliniz
}

/*
 * --------------Tapşırıq 1------------2  : Massivdəki təkrarlanan elementləri silin
 * 
 * Təsvir: Verilmiş massivdən təkrarlanan elementləri silib, hər bir elementdən
 * yalnız bir dənə olan yeni massiv qaytarın.
 * 
 * Giriş: Hər hansı tiplə elementlərdən ibarət massiv. Məsələn: [1, 2, 2, 3, 3, 3, 4, 5, 5]
 * Çıxış: Təkrarsız elementlərdən ibarət massiv. Yuxarıdakı nümunə üçün: [1, 2, 3, 4, 5]
 * 
 * İstifadə nümunəsi:
 * removeDuplicates([1, 2, 2, 3, 3, 3, 4]); // [1, 2, 3, 4]
 * removeDuplicates(["a", "b", "a", "c", "b"]); // ["a", "b", "c"]
 * removeDuplicates([1, 1, 1, 1]); // [1]
 */
function removeDuplicates(arr) {
  // Həlliniz
}

/*
 * --------------Tapşırıq 1------------3  : İki massivin kəsişməsini tapın
 * 
 * Təsvir: İki massiv arasında ortaq olan elementləri (kəsişməni) tapın.
 * Nəticə massivində hər ortaq element yalnız bir dəfə olmalıdır.
 * 
 * Giriş: İki massiv. Məsələn: [1, 2, 3, 4, 5] və [3, 4, 5, 6, 7]
 * Çıxış: Ortaq elementlərdən ibarət massiv. Yuxarıdakı nümunə üçün: [3, 4, 5]
 * 
 * İstifadə nümunəsi:
 * findIntersection([1, 2, 3], [3, 4, 5]); // [3]
 * findIntersection([1, 1, 2, 3], [1, 3, 3, 4]); // [1, 3]
 * findIntersection([1, 2, 3], [4, 5, 6]); // []
 */
function findIntersection(arr1, arr2) {
  // Həlliniz
}

/*
 * --------------Tapşırıq 1------------4  : İki mətinin anaqram olub-olmadığını yoxlayın
 * 
 * Təsvir: İki mətnin anaqram olub-olmadığını yoxlayın. Anaqram - eyni hərflərdən
 * təşkil olunmuş fərqli sözlərdir. Böyük/kiçik hərf fərqi nəzərə alınmamalı və
 * yalnız hərf olmayan simvollar (boşluqlar, durğu işarələri) nəzərə alınmamalıdır.
 * 
 * Giriş: İki mətn. Məsələn: "listen" və "silent"
 * Çıxış: true və ya false. Yuxarıdakı nümunə üçün: true
 * 
 * İstifadə nümunəsi:
 * areAnagrams("listen", "silent"); // true
 * areAnagrams("triangle", "integral"); // true
 * areAnagrams("hello", "world"); // false
 * areAnagrams("The Morse Code", "Here come dots"); // true
 */
function areAnagrams(str1, str2) {
  // Həlliniz
}

/*
 * --------------Tapşırıq 1------------5  : Ədədlər massivinin orta qiymətini hesablayın
 * 
 * Təsvir: Verilmiş ədədlər massivinin orta qiymətini (cəmin element sayına nisbəti)
 * hesablayın.
 * 
 * Giriş: Ədədlər massivi. Məsələn: [1, 2, 3, 4, 5]
 * Çıxış: Orta qiymət. Yuxarıdakı nümunə üçün: 3
 * 
 * İstifadə nümunəsi:
 * calculateAverage([1, 2, 3, 4, 5]); // 3
 * calculateAverage([10, 20]); // 15
 * calculateAverage([2, 4, 6, 8, 10]); // 6
 */
function calculateAverage(arr) {
  // Həlliniz
}

/*
 * --------------Tapşırıq 1------------6  : Ardıcıl ədədlər massivində çatışmayan ədədi tapın
 * 
 * Təsvir: Verilmiş massiv 1-dən n-ə qədər olan ardıcıl ədədləri ehtiva edir,
 * lakin bir ədəd çatışmır. Bu çatışmayan ədədi tapın.
 * 
 * Giriş: Ardıcıl ədədlər massivi, bir çatışmayan ədədlə. Məsələn: [1, 2, 4, 5]
 * Çıxış: Çatışmayan ədəd. Yuxarıdakı nümunə üçün: 3
 * 
 * İstifadə nümunəsi:
 * findMissingNumber([1, 2, 4, 5]); // 3
 * findMissingNumber([1, 3]); // 2
 * findMissingNumber([2, 3, 4, 5, 6]); // 1 (diqqət edin: 1 çatışmır)
 */
function findMissingNumber(arr) {
  // Həlliniz
}

/*
 * --------------Tapşırıq 1------------7  : Mətndəki hər sözün ilk hərfini böyük hərfə çevirin
 * 
 * Təsvir: Verilmiş mətndəki hər sözün ilk hərfini böyük, qalan hərflərini
 * kiçik hərfə çevirən funksiya yazın.
 * 
 * Giriş: Mətn. Məsələn: "hello world"
 * Çıxış: Hər sözün ilk hərfi böyük olan mətn. Yuxarıdakı nümunə üçün: "Hello World"
 * 
 * İstifadə nümunəsi:
 * capitalizeWords("hello world"); // "Hello World"
 * capitalizeWords("javascript is awesome"); // "Javascript Is Awesome"
 * capitalizeWords("a b c"); // "A B C"
 */
function capitalizeWords(str) {
  // Həlliniz
}

/*
 * --------------Tapşırıq 1------------8  : Mətndəki ən uzun sözü tapın
 * 
 * Təsvir: Verilmiş mətndəki ən uzun sözü tapın. Əgər birdən çox söz eyni
 * uzunluğa malikdirsə, ilk rast gəlinəni qaytarın.
 * 
 * Giriş: Sözlərdən ibarət mətn. Məsələn: "Bu bir nümunə cümlədir"
 * Çıxış: Ən uzun söz. Yuxarıdakı nümunə üçün: "nümunə"
 * 
 * İstifadə nümunəsi:
 * findLongestWord("Bu bir nümunə cümlədir"); // "nümunə"
 * findLongestWord("JavaScript proqramlaşdırma dilidir"); // "proqramlaşdırma"
 * findLongestWord("a bb ccc"); // "ccc"
 */
function findLongestWord(str) {
  // Həlliniz
}

/*
 * --------------Tapşırıq 1------------9  : Ədədin sadə olub-olmadığını yoxlayın
 * 
 * Təsvir: Verilmiş ədədin sadə olub-olmadığını təyin edin. Sadə ədəd yalnız
 * 1-ə və özünə qalıqsız bölünən ədəddir. 1 sadə ədəd deyil.
 * 
 * Giriş: Tam ədəd. Məsələn: 17
 * Çıxış: true (sadə) və ya false (sadə deyil). Yuxarıdakı nümunə üçün: true
 * 
 * İstifadə nümunəsi:
 * isPrime(17); // true
 * isPrime(4); // false
 * isPrime(1); // false
 * isPrime(2); // true
 */
function isPrime(num) {
  // Həlliniz
}

/*
 * --------------Tapşırıq 2------------0  : n elementə qədər Fibonaççi ardıcıllığını yaradın
 * 
 * Təsvir: İlk n sayda Fibonaççi ədədlərini hesablayın. Fibonaççi ardıcıllığı
 * 0, 1 ilə başlayır və hər sonrakı ədəd özündən əvvəlki iki ədədin cəminə
 * bərabərdir: 0, 1, 1, 2, 3, 5, 8, 13, 21, ...
 * 
 * Giriş: n ədədi (tam müsbət). Məsələn: 8
 * Çıxış: İlk n Fibonaççi ədədindən ibarət massiv. Yuxarıdakı nümunə üçün: [0, 1, 1, 2, 3, 5, 8, 13]
 * 
 * İstifadə nümunəsi:
 * fibonacciSequence(5); // [0, 1, 1, 2, 3]
 * fibonacciSequence(8); // [0, 1, 1, 2, 3, 5, 8, 13]
 * fibonacciSequence(1); // [0]
 */
function fibonacciSequence(n) {
  // Həlliniz
}

// ===== SƏVİYYƏ 3: DATA STRUKTUR VƏ ALQORİTMLƏR =====

/*
 * --------------Tapşırıq 2------------1  : İkili Axtarış (Binary Search) alqoritmini yazın
 * 
 * Təsvir: İkili axtarış metodu ilə sıralanmış massivdə verilmiş elementin
 * indeksini tapın. Əgər element massivdə yoxdursa, -1 qaytarın.
 * İkili axtarış - hər dəfə massivi iki hissəyə bölərək, elementin hansı
 * hissədə ola biləcəyini müəyyən edən alqoritmdir.
 * 
 * Giriş: Sıralanmış massiv və axtarılan dəyər. Məsələn: [1, 3, 5, 7, 9, 11, 13], 7
 * Çıxış: Axtarılan dəyərin indeksi və ya -1. Yuxarıdakı nümunə üçün: 3
 * 
 * İstifadə nümunəsi:
 * binarySearch([1, 3, 5, 7, 9], 5); // 2
 * binarySearch([1, 3, 5, 7, 9], 6); // -1
 * binarySearch([1, 3, 5, 7, 9], 1); // 0
 */
function binarySearch(arr, target) {
  // Həlliniz
}

/*
 * --------------Tapşırıq 2------------2  : Qabarcıq Sıralama (Bubble Sort) alqoritmini yazın
 * 
 * Təsvir: Qabarcıq sıralama metodu ilə massivi artan sıra ilə sıralayın.
 * Bu alqoritm yanaşı elementləri müqayisə edir və lazım gəldikdə onların
 * yerini dəyişir. Proses bütün massiv sıralanana qədər təkrarlanır.
 * 
 * Giriş: Sıralanmamış massiv. Məsələn: [5, 3, 8, 4, 2]
 * Çıxış: Artan sıra ilə sıralanmış massiv. Yuxarıdakı nümunə üçün: [2, 3, 4, 5, 8]
 * 
 * İstifadə nümunəsi:
 * bubbleSort([5, 3, 8, 4, 2]); // [2, 3, 4, 5, 8]
 * bubbleSort([5, 1, 4, 2, 8]); // [1, 2, 4, 5, 8]
 * bubbleSort([3, 1, 3, 2, 5]); // [1, 2, 3, 3, 5]
 */
function bubbleSort(arr) {
  // Həlliniz
}

/*
 * --------------Tapşırıq 2------------3  : Seçim Sıralama (Selection Sort) alqoritmini yazın
 * 
 * Təsvir: Seçim sıralama metodu ilə massivi artan sıra ilə sıralayın.
 * Bu alqoritm hər iterasiyada massivdəki ən kiçik elementi tapıb
 * müvafiq mövqeyə yerləşdirir.
 * 
 * Giriş: Sıralanmamış massiv. Məsələn: [64, 25, 12, 22, 11]
 * Çıxış: Artan sıra ilə sıralanmış massiv. Yuxarıdakı nümunə üçün: [11, 12, 22, 25, 64]
 * 
 * İstifadə nümunəsi:
 * selectionSort([64, 25, 12, 22, 11]); // [11, 12, 22, 25, 64]
 * selectionSort([5, 1, 3, 2, 4]); // [1, 2, 3, 4, 5]
 */
function selectionSort(arr) {
  // Həlliniz
}

/*
 * --------------Tapşırıq 2------------4  : Daxiletmə Sıralama (Insertion Sort) alqoritmini yazın
 * 
 * Təsvir: Daxiletmə sıralama metodu ilə massivi artan sıra ilə sıralayın.
 * Bu alqoritm kartları əlinizdə sıralamağa bənzəyir - hər yeni elementi
 * artıq sıralanmış hissədə düzgün yerinə yerləşdirir.
 * 
 * Giriş: Sıralanmamış massiv. Məsələn: [12, 11, 13, 5, 6]
 * Çıxış: Artan sıra ilə sıralanmış massiv. Yuxarıdakı nümunə üçün: [5, 6, 11, 12, 13]
 * 
 * İstifadə nümunəsi:
 * insertionSort([12, 11, 13, 5, 6]); // [5, 6, 11, 12, 13]
 * insertionSort([4, 3, 2, 10, 12, 1, 5, 6]); // [1, 2, 3, 4, 5, 6, 10, 12]
 */
function insertionSort(arr) {
  // Həlliniz
}

/*
 * --------------Tapşırıq 2------------5  : Massivdə ən çox təkrarlanan elementi tapın
 * 
 * Təsvir: Verilmiş massivdə ən çox təkrarlanan elementi tapın. Əgər bir neçə
 * element eyni maksimum sayda təkrarlanırsa, onlardan birini qaytara bilərsiniz.
 * 
 * Giriş: Elementlər massivi. Məsələn: [1, 3, 2, 3, 4, 1, 3, 5, 3]
 * Çıxış: Ən çox təkrarlanan element. Yuxarıdakı nümunə üçün: 3 (4 dəfə təkrarlanıb)
 * 
 * İstifadə nümunəsi:
 * findMostFrequent([1, 3, 2, 3, 4, 1, 3, 5, 3]); // 3
 * findMostFrequent(["a", "b", "a", "c", "b", "a"]); // "a"
 * findMostFrequent([3, 'a', 3, 'a', 'a', 2, 3, 'a', 3]); // "a" və ya 3
 */
function findMostFrequent(arr) {
  // Həlliniz
}



/*
 * --------------Tapşırıq 2------------6  : Massivlər istifadə edərək Növbə (Queue) yaradın
 * 
 * Təsvir: Növbə (Queue) - FIFO (First In First Out) prinsipi ilə işləyən data strukturudur.
 * Yəni, ilk daxil olan element ilk çıxacaq. Növbə bir çox proqramlaşdırma
 * tapşırıqlarında istifadə olunur (məsələn, print növbəsi, proseslərin növbəsi, və s.)
 * 
 * Növbəni massiv istifadə edərək yaradın və aşağıdakı əməliyyatları təmin edin:
 * - enqueue(item): Növbənin sonuna element əlavə edir
 * - dequeue(): Növbənin əvvəlindən elementi çıxarır və qaytarır
 * - peek(): Növbənin əvvəlindəki elementi qaytarır (silmədən)
 * - isEmpty(): Növbənin boş olub-olmadığını yoxlayır
 * - size(): Növbədəki elementlərin sayını qaytarır
 * 
 * Giriş/Çıxış: Queue sinfi və onun metodları
 * 
 * İstifadə nümunəsi:
 * const queue = new Queue();
 * queue.enqueue(1);
 * queue.enqueue(2);
 * queue.enqueue(3);
 * console.log(queue.peek()); // 1
 * console.log(queue.dequeue()); // 1
 * console.log(queue.size()); // 2
 * console.log(queue.isEmpty()); // false
 */
class Queue {
  constructor() {
    // Həlliniz
  }
  
  // Metodları yazın
}

/*
 * --------------Tapşırıq 2------------7  : Massivlər istifadə edərək Stek (Stack) yaradın
 * 
 * Təsvir: Stek (Stack) - LIFO (Last In First Out) prinsipi ilə işləyən data strukturudur.
 * Yəni, son daxil olan element ilk çıxacaq. Stek bir çox proqramlaşdırma 
 * tapşırıqlarında istifadə olunur (məsələn, geri qayıtma funksiyası, ləğv etmə əməliyyatı).
 * 
 * Steki massiv istifadə edərək yaradın və aşağıdakı əməliyyatları təmin edin:
 * - push(item): Stekin üstünə element əlavə edir
 * - pop(): Stekin üstündən elementi çıxarır və qaytarır
 * - peek(): Stekin üstündəki elementi qaytarır (silmədən)
 * - isEmpty(): Stekin boş olub-olmadığını yoxlayır
 * - size(): Stekdəki elementlərin sayını qaytarır
 * 
 * Giriş/Çıxış: Stack sinfi və onun metodları
 * 
 * İstifadə nümunəsi:
 * const stack = new Stack();
 * stack.push(1);
 * stack.push(2);
 * stack.push(3);
 * console.log(stack.peek()); // 3
 * console.log(stack.pop()); // 3
 * console.log(stack.size()); // 2
 * console.log(stack.isEmpty()); // false
 */
class Stack {
  constructor() {
    // Həlliniz
  }
  
  // Metodları yazın
}

/*
 * --------------Tapşırıq 2------------8  : Mötərizələrin düzgün olub-olmadığını yoxlayın
 * 
 * Təsvir: Verilmiş mətndə mötərizələrin düzgün açılıb-bağlanmasını yoxlayın.
 * Üç növ mötərizə var: "()", "{}", "[]". Mötərizələr düzgün hesab olunur əgər:
 * - Hər bir açılan mötərizəyə uyğun eyni növdən bağlanan mötərizə varsa
 * - Açılan mötərizələr düzgün ardıcıllıqla bağlanırsa
 * 
 * Məsələn, "{[()]}" düzgündür, amma "([)]" yanlışdır. Bu məsələni həll etmək
 * üçün stek data strukturundan istifadə etmək əlverişlidir.
 * 
 * Giriş: Mötərizələrdən ibarət mətn. Məsələn: "({[]})"
 * Çıxış: true (düzgündür) və ya false (yanlışdır)
 * 
 * İstifadə nümunəsi:
 * hasValidParentheses("()"); // true
 * hasValidParentheses("()[]{}"); // true
 * hasValidParentheses("(]"); // false
 * hasValidParentheses("([)]"); // false
 * hasValidParentheses("{[]}"); // true
 */
function hasValidParentheses(str) {
  // Həlliniz
}

/*
 * --------------Tapşırıq 2------------9  : İki sıralanmış massivi birləşdirin
 * 
 * Təsvir: İki ayrı sıralanmış massivi birləşdirib, tək bir sıralanmış massiv yaradın.
 * Bu əməliyyat O(n+m) zaman mürəkkəbliyində həyata keçirilməlidir, burada n və m 
 * müvafiq massivlərin uzunluqlarıdır.
 * 
 * Bu məsələ, Birləşdirmə Sıralaması (Merge Sort) alqoritmində istifadə olunan 
 * əsas əməliyyatdır.
 * 
 * Giriş: İki sıralanmış massiv. Məsələn: [1, 3, 5, 7], [2, 4, 6, 8]
 * Çıxış: Birləşdirilmiş və sıralanmış massiv. Yuxarıdakı nümunə üçün: [1, 2, 3, 4, 5, 6, 7, 8]
 * 
 * İstifadə nümunəsi:
 * mergeSortedArrays([1, 3, 5], [2, 4, 6]); // [1, 2, 3, 4, 5, 6]
 * mergeSortedArrays([1, 5, 9], [2, 6, 10]); // [1, 2, 5, 6, 9, 10]
 * mergeSortedArrays([1, 2, 3], []); // [1, 2, 3]
 */
function mergeSortedArrays(arr1, arr2) {
  // Həlliniz
}

/*
 * --------------Tapşırıq 3------------0  : İç-içə massivi düzləşdirin
 * 
 * Təsvir: Verilmiş iç-içə massivi (massivlər içində massivlər) vahid, tək-səviyyəli
 * massivə çevirin. Massiv istənilən dərinlikdə iç-içə ola bilər.
 * 
 * Məsələn, [1, [2, [3, 4], 5], 6] massivi [1, 2, 3, 4, 5, 6] kimi düzləşdirilməlidir.
 * Bu məsələni həll etmək üçün rekursiya və ya stack istifadə edilə bilər.
 * 
 * Giriş: İç-içə massiv. Məsələn: [1, [2, [3]], 4, [5, 6]]
 * Çıxış: Düzləşdirilmiş massiv. Yuxarıdakı nümunə üçün: [1, 2, 3, 4, 5, 6]
 * 
 * İstifadə nümunəsi:
 * flattenArray([1, [2, 3], 4]); // [1, 2, 3, 4]
 * flattenArray([1, [2, [3, 4], 5], 6]); // [1, 2, 3, 4, 5, 6]
 * flattenArray([1, [], 3, []]); // [1, 3]
 */
function flattenArray(arr) {
  // Həlliniz
}

// ===== SƏVİYYƏ 4: MÜRƏKKƏB ALQORİTMLƏR =====

/*
 * --------------Tapşırıq 3------------1  : Əlaqəli siyahı (Linked List) yaradın
 * 
 * Təsvir: Əlaqəli siyahı (Linked List) - hər bir elementin (düyünün) həm məlumatı, 
 * həm də növbəti elementə istinadı saxladığı xətti data strukturudur. 
 * 
 * Əlaqəli siyahıda həyata keçirilməli olan əsas əməliyyatlar:
 * - append(value): Siyahının sonuna element əlavə edir
 * - prepend(value): Siyahının əvvəlinə element əlavə edir
 * - delete(value): Verilmiş dəyərə malik elementi silir
 * - find(value): Verilmiş dəyərə malik elementi tapır və qaytarır
 * - toArray(): Siyahını massivə çevirir
 * 
 * Həmçinin, düyün strukturunu da yaratmalısınız ki, bu da data saxlayacaq və
 * növbəti düyünə istinad edəcək.
 * 
 * Giriş/Çıxış: LinkedList sinfi və onun metodları
 * 
 * İstifadə nümunəsi:
 * const list = new LinkedList();
 * list.append(1);
 * list.append(2);
 * list.prepend(0);
 * console.log(list.toArray()); // [0, 1, 2]
 * list.delete(1);
 * console.log(list.toArray()); // [0, 2]
 * console.log(list.find(2)); // Düyün {value: 2, next: null}
 */
class LinkedList {
  constructor() {
    // Həlliniz
  }
  
  // Metodları yazın
}

/*
 * --------------Tapşırıq 3------------2  : İkili axtarış ağacı (Binary Search Tree) yaradın
 * 
 * Təsvir: İkili axtarış ağacı (BST) - hər bir düyünün ən çoxu iki övladı olan ağac 
 * strukturudur. Düyünlər elə yerləşdirilir ki, hər bir düyünün sol altağacındakı 
 * bütün düyünlərin dəyərləri onun dəyərindən kiçik, sağ altağacındakı bütün 
 * düyünlərin dəyərləri isə onun dəyərindən böyük olur.
 * 
 * BST-də həyata keçirilməli olan əsas əməliyyatlar:
 * - insert(value): Ağaca yeni element əlavə edir
 * - search(value): Ağacda elementi axtarır
 * - delete(value): Ağacdan elementi silir
 * - min(): Ağacdakı minimum dəyəri tapır
 * - max(): Ağacdakı maksimum dəyəri tapır
 * 
 * Həmçinin, düyün strukturunu da yaratmalısınız ki, bu da data saxlayacaq və
 * sol və sağ övladlara istinad edəcək.
 * 
 * Giriş/Çıxış: BinarySearchTree sinfi və onun metodları
 * 
 * İstifadə nümunəsi:
 * const bst = new BinarySearchTree();
 * bst.insert(10);
 * bst.insert(5);
 * bst.insert(15);
 * console.log(bst.search(10)); // true
 * console.log(bst.min()); // 5
 * console.log(bst.max()); // 15
 * bst.delete(5);
 * console.log(bst.search(5)); // false
 */
class BinarySearchTree {
  constructor() {
    // Həlliniz
  }
  
  // Metodları yazın
}

/*
 * --------------Tapşırıq 3------------3  : Pul dəyişimi məsələsi (Coin Change Problem)
 * 
 * Təsvir: Verilmiş məbləği yaratmaq üçün lazım olan minimum sikkə sayını tapın.
 * Sizə sikkə nominalları massivi və hədəf məbləğ verilir. Hər nominaldakı sikkədən
 * istədiyiniz qədər istifadə edə bilərsiniz.
 * 
 * Bu məsələ dinamik proqramlaşdırma (dynamic programming) ilə həll olunur.
 * 
 * Giriş: Sikkə nominalları massivi və hədəf məbləğ. Məsələn: [1, 2, 5], 11
 * Çıxış: Minimum sikkə sayı. Yuxarıdakı nümunə üçün: 3 (5 + 5 + 1)
 * 
 * İstifadə nümunəsi:
 * minCoins([1, 2, 5], 11); // 3
 * minCoins([1, 3, 4, 5], 7); // 2 (3 + 4)
 * minCoins([2], 3); // -1 (mümkün deyil)
 */
function minCoins(coins, amount) {
  // Həlliniz
}

/*
 * --------------Tapşırıq 3------------4  : Ən uzun ortaq altardıcıllıq (Longest Common Subsequence)
 * 
 * Təsvir: İki mətn arasında ən uzun ortaq altardıcıllığın uzunluğunu tapın.
 * Altardıcıllıq - əsl ardıcıllıqdan elementləri silərək (bəzilərini və ya heç birini 
 * silməyərək, amma elementlərin sırasını dəyişdirmədən) əldə edilən ardıcıllıqdır.
 * 
 * Məsələn, "ace" mətni "abcde" mətninin bir altardıcıllığıdır.
 * Bu məsələ dinamik proqramlaşdırma (dynamic programming) ilə həll olunur.
 * 
 * Giriş: İki mətn. Məsələn: "abcde" və "ace"
 * Çıxış: Ən uzun ortaq altardıcıllığın uzunluğu. Yuxarıdakı nümunə üçün: 3
 * 
 * İstifadə nümunəsi:
 * longestCommonSubsequence("abcde", "ace"); // 3
 * longestCommonSubsequence("abc", "abc"); // 3
 * longestCommonSubsequence("abc", "def"); // 0
 */
function longestCommonSubsequence(str1, str2) {
  // Həlliniz
}

/*
 * --------------Tapşırıq 3------------5  : Cəld Sıralama (Quick Sort) alqoritmini yazın
 * 
 * Təsvir: Cəld Sıralama (Quick Sort) - bölünüb-birləşdirmə prinsipi ilə işləyən 
 * effektiv sıralama alqoritmidir. Orta halda O(n log n) zaman mürəkkəbliyinə malikdir.
 * 
 * Alqoritmin işləmə prinsipi:
 * 1. Massivdən bir dayaq element (pivot) seçilir
 * 2. Massiv iki hissəyə bölünür: dayaq elementdən kiçik və böyük elementlər
 * 3. Hər iki hissə rekursiv olaraq sıralanır
 * 4. Sıralanmış hissələr birləşdirilir
 * 
 * Giriş: Sıralanmamış massiv. Məsələn: [10, 80, 30, 90, 40, 50, 70]
 * Çıxış: Sıralanmış massiv. Yuxarıdakı nümunə üçün: [10, 30, 40, 50, 70, 80, 90]
 * 
 * İstifadə nümunəsi:
 * quickSort([10, 80, 30, 90, 40, 50, 70]); // [10, 30, 40, 50, 70, 80, 90]
 * quickSort([1, 5, 3, 2, 8, 7, 6, 4]); // [1, 2, 3, 4, 5, 6, 7, 8]
 */
function quickSort(arr) {
  // Həlliniz
}

/*
 * --------------Tapşırıq 3------------6  : Birləşdirmə Sıralama (Merge Sort) alqoritmini yazın
 * 
 * Təsvir: Birləşdirmə Sıralama (Merge Sort) - bölünüb-birləşdirmə prinsipi ilə işləyən
 * stabil sıralama alqoritmidir. Həmişə O(n log n) zaman mürəkkəbliyinə malikdir.
 * 
 * Alqoritmin işləmə prinsipi:
 * 1. Massiv ortadan iki hissəyə bölünür
 * 2. Hər iki hissə rekursiv olaraq sıralanır
 * 3. Sıralanmış hissələr birləşdirilir
 * 
 * Giriş: Sıralanmamış massiv. Məsələn: [38, 27, 43, 3, 9, 82, 10]
 * Çıxış: Sıralanmış massiv. Yuxarıdakı nümunə üçün: [3, 9, 10, 27, 38, 43, 82]
 * 
 * İstifadə nümunəsi:
 * mergeSort([38, 27, 43, 3, 9, 82, 10]); // [3, 9, 10, 27, 38, 43, 82]
 * mergeSort([5, 2, 3, 1, 4]); // [1, 2, 3, 4, 5]
 */
function mergeSort(arr) {
  // Həlliniz
}

/*
 * --------------Tapşırıq 3------------7  : Mətnin bütün permutasiyalarını tapın
 * 
 * Təsvir: Verilmiş mətnin bütün mümkün permutasiyalarını (yerdəyişmələrini) tapın.
 * Permutasiya - elementlərin sırasının müxtəlif variantlarıdır.
 * 
 * Məsələn, "abc" mətninin permutasiyaları: "abc", "acb", "bac", "bca", "cab", "cba".
 * n uzunluqlu mətinin n! (n faktorial) sayda permutasiyası var.
 * Bu məsələni rekursiya ilə həll etmək olar.
 * 
 * Giriş: Mətn. Məsələn: "abc"
 * Çıxış: Bütün mümkün permutasiyalardan ibarət massiv. 
 * Yuxarıdakı nümunə üçün: ["abc", "acb", "bac", "bca", "cab", "cba"]
 * 
 * İstifadə nümunəsi:
 * findPermutations("abc"); // ["abc", "acb", "bac", "bca", "cab", "cba"]
 * findPermutations("ab"); // ["ab", "ba"]
 * findPermutations("a"); // ["a"]
 */
function findPermutations(str) {
  // Həlliniz
}

/*
 * --------------Tapşırıq 3------------8  : Maksimum altmassiv cəmi (Kadane alqoritmi)
 * 
 * Təsvir: Verilmiş ədədlər massivində ardıcıl elementlərdən ibarət ən böyük cəmə
 * malik altmassivi tapın. Kadane alqoritmi bu məsələni O(n) zaman mürəkkəbliyində 
 * həll edir.
 * 
 * Alqoritmin əsas ideyası - hər addımda hazırkı altmassivin məcmu (cari) cəmini və 
 * ümumi maksimum cəmi saxlamaqdır.
 * 
 * Giriş: Müsbət və mənfi ədədlərdən ibarət massiv. Məsələn: [-2, 1, -3, 4, -1, 2, 1, -5, 4]
 * Çıxış: Maksimum cəm. Yuxarıdakı nümunə üçün: 6 (altmassiv [4, -1, 2, 1])
 * 
 * İstifadə nümunəsi:
 * maxSubarraySum([-2, 1, -3, 4, -1, 2, 1, -5, 4]); // 6
 * maxSubarraySum([1, 2, 3, -2, 5]); // 9
 * maxSubarraySum([-1, -2, -3]); // -1
 */
function maxSubarraySum(arr) {
  // Həlliniz
}

/*
 * --------------Tapşırıq 3------------9  : Massivin bütün alt çoxluqlarını tapın (Qüvvət çoxluğu)
 * 
 * Təsvir: Verilmiş massivin bütün mümkün alt çoxluqlarını (qüvvət çoxluğunu) tapın.
 * n elementli çoxluğun 2^n sayda alt çoxluğu var, boş çoxluq da daxil olmaqla.
 * 
 * Məsələn, [1, 2, 3] massivinin alt çoxluqları: [], [1], [2], [3], [1, 2], [1, 3], [2, 3], [1, 2, 3].
 * Bu məsələni binar maskalanma və ya rekursiya ilə həll etmək olar.
 * 
 * Giriş: Unikal elementlərdən ibarət massiv. Məsələn: [1, 2, 3]
 * Çıxış: Bütün mümkün alt çoxluqlardan ibarət massiv.
 * Yuxarıdakı nümunə üçün: [[], [1], [2], [1, 2], [3], [1, 3], [2, 3], [1, 2, 3]]
 * 
 * İstifadə nümunəsi:
 * findSubsets([1, 2, 3]); // [[], [1], [2], [1, 2], [3], [1, 3], [2, 3], [1, 2, 3]]
 * findSubsets([1, 2]); // [[], [1], [2], [1, 2]]
 * findSubsets([]); // [[]] (yalnız boş çoxluq)
 */
function findSubsets(arr) {
  // Həlliniz
}

/*
 * --------------Tapşırıq 4------------0  : Qraf (Qonşu siyahısı ilə) yaradın
 * 
 * Təsvir: Qraf - təpələr (vertexes) və bu təpələri birləşdirən tillərdən (edges) ibarət 
 * data strukturudur. Qraf qonşu siyahısı (adjacency list) istifadə edərək təmsil oluna bilər, 
 * burada hər təpə üçün onunla birləşən təpələr siyahısı saxlanılır.
 * 
 * Qrafda həyata keçirilməli olan əsas əməliyyatlar:
 * - addVertex(vertex): Qrafa yeni təpə əlavə edir
 * - addEdge(vertex1, vertex2): İki təpə arasında til əlavə edir
 * - removeVertex(vertex): Qrafdan təpəni və ona aid bütün tilləri silir
 * - removeEdge(vertex1, vertex2): İki təpə arasındakı tili silir
 * - dfs(startVertex): Dərinlik əsaslı axtarış (Depth-First Search) yerinə yetirir
 * - bfs(startVertex): Genişlik əsaslı axtarış (Breadth-First Search) yerinə yetirir
 * 
 * Giriş/Çıxış: Graph sinfi və onun metodları
 * 
 * İstifadə nümunəsi:
 * const graph = new Graph();
 * graph.addVertex("A");
 * graph.addVertex("B");
 * graph.addVertex("C");
 * graph.addEdge("A", "B");
 * graph.addEdge("A", "C");
 * console.log(graph.dfs("A")); // ["A", "B", "C"]
 * graph.removeEdge("A", "C");
 * console.log(graph.bfs("A")); // ["A", "B"]
 */
class Graph {
  constructor() {
    // Həlliniz
  }
  
  // Metodları yazın
}

// ===== SƏVİYYƏ 5: EKSPERT ALQORİTMLƏR =====

/*
 * --------------Tapşırıq 4------------1  : Ən uzun artan altardıcıllığı tapın (Longest Increasing Subsequence)
 * 
 * Təsvir: Verilmiş ədədlər massivində ən uzun artan altardıcıllığın uzunluğunu tapın.
 * Artan altardıcıllıq - elementləri sıra ilə artan olan altardıcıllıqdır.
 * 
 * Məsələn, [10, 9, 2, 5, 3, 7, 101, 18] massivində ən uzun artan altardıcıllıq
 * [2, 3, 7, 18] və ya [2, 3, 7, 101] ola bilər, uzunluğu 4-dür.
 * 
 * Bu məsələ dinamik proqramlaşdırma (dynamic programming) və ya ikili axtarış
 * (binary search) ilə həll oluna bilər.
 * 
 * Giriş: Ədədlər massivi. Məsələn: [10, 9, 2, 5, 3, 7, 101, 18]
 * Çıxış: Ən uzun artan altardıcıllığın uzunluğu. Yuxarıdakı nümunə üçün: 4
 * 
 * İstifadə nümunəsi:
 * longestIncreasingSubsequence([10, 9, 2, 5, 3, 7, 101, 18]); // 4
 * longestIncreasingSubsequence([7, 7, 7, 7]); // 1
 * longestIncreasingSubsequence([0, 1, 0, 3, 2, 3]); // 4
 */
function longestIncreasingSubsequence(arr) {
  // Həlliniz
}



/*
 * --------------Tapşırıq 4------------2  : Ən qısa yol üçün Dijkstra alqoritmini yazın
 * 
 * Təsvir: Dijkstra alqoritmi - çəkili qrafda başlanğıc təpədən bütün digər təpələrə
 * (və ya konkret bir hədəf təpəyə) ən qısa yolu tapmaq üçün istifadə olunan alqoritmdir.
 * 
 * Alqoritmin işləmə prinsipi:
 * 1. Başlanğıc təpəni ziyarət edilmiş kimi işarələyin və ona qədərki məsafəni 0 kimi təyin edin
 * 2. Digər bütün təpələrə qədərki məsafəni sonsuz kimi təyin edin
 * 3. Hazırkı təpənin bütün qonşularını araşdırın və onlara qədərki məsafəni yeniləyin
 * 4. Ziyarət edilməmiş təpələr arasında ən kiçik məsafəyə malik təpəni seçin
 * 5. 3-4-cü addımları bütün təpələr ziyarət edilənə qədər və ya hədəf təpəyə çatana qədər təkrarlayın
 * 
 * Bu alqoritm naviqasiya sistemlərində, şəbəkə marşrutlaşdırmasında və oyun AI-də geniş istifadə olunur.
 * 
 * Giriş: 
 * - graph: Qonşu siyahısı (adjacency list) formatında çəkili qraf. 
 *   Məsələn: { 'A': { 'B': 4, 'C': 2 }, 'B': { 'D': 5 }, 'C': { 'B': 1, 'D': 8 }, 'D': { } }
 * - start: Başlanğıc təpə. Məsələn: 'A'
 * - end: Son təpə. Məsələn: 'D'
 * 
 * Çıxış: 
 * - Ən qısa yol və məsafə. Məsələn: { distance: 7, path: ['A', 'C', 'B', 'D'] }
 * 
 * İstifadə nümunəsi:
 * const graph = {
 *   'A': { 'B': 4, 'C': 2 },
 *   'B': { 'D': 5 },
 *   'C': { 'B': 1, 'D': 8 },
 *   'D': { }
 * };
 * dijkstra(graph, 'A', 'D'); // { distance: 7, path: ['A', 'C', 'B', 'D'] }
 */
function dijkstra(graph, start, end) {
  // Həlliniz
}

/*
 * --------------Tapşırıq 4------------3  : Əlaqəli siyahıda dövr olub-olmadığını yoxlayın
 * 
 * Təsvir: Verilmiş əlaqəli siyahıda dövr (cycle) olub-olmadığını təyin edin.
 * Dövr o zaman yaranır ki, hər hansı bir düyün özünə qayıdır.
 * 
 * Bu məsələni həll etmək üçün "yavaş" və "sürətli" göstəricilər (pointers) metodundan
 * istifadə edə bilərsiniz. "Yavaş" göstərici hər addımda bir düyün, "sürətli" göstərici
 * isə hər addımda iki düyün irəliləyir. Əgər dövr varsa, "sürətli" göstərici "yavaş"
 * göstəriciyə çatacaq. 
 * 
 * Bu alqoritm Floyd's Cycle-Finding Algorithm və ya "Tısbağa və dovşan" alqoritmi 
 * kimi tanınır.
 * 
 * Giriş: Əlaqəli siyahının başlanğıc düyünü (head)
 * Çıxış: true (dövr var) və ya false (dövr yoxdur)
 * 
 * İstifadə nümunəsi:
 * // Dövrsüz əlaqəli siyahı: 1 -> 2 -> 3 -> null
 * const head1 = { val: 1, next: { val: 2, next: { val: 3, next: null } } };
 * hasCycle(head1); // false
 * 
 * // Dövrü olan əlaqəli siyahı: 1 -> 2 -> 3 -> 1
 * const head2 = { val: 1, next: { val: 2, next: { val: 3, next: null } } };
 * head2.next.next.next = head2; // Dövr yaradırıq
 * hasCycle(head2); // true
 */
function hasCycle(head) {
  // Həlliniz
}

/*
 * --------------Tapşırıq 4------------4  : Trie (Prefiks ağacı) yaradın
 * 
 * Təsvir: Trie (və ya Prefiks ağacı) - sözləri və ya ardıcıllıqları saxlamaq və axtarmaq
 * üçün istifadə olunan ağac data strukturudur. Hər bir düyün bir hərfi təmsil edir və
 * uşaqları onun ardınca gələn mümkün hərfləri təmsil edir.
 * 
 * Trie-də həyata keçirilməli olan əsas əməliyyatlar:
 * - insert(word): Ağaca yeni söz əlavə edir
 * - search(word): Ağacda tam sözü axtarır
 * - startsWith(prefix): Verilmiş prefikslə başlayan sözün olub-olmadığını yoxlayır
 * 
 * Trie strukturu autocomplete, spell checker, və lüğətlər kimi tətbiqlərdə geniş
 * istifadə olunur.
 * 
 * Giriş/Çıxış: Trie sinfi və onun metodları
 * 
 * İstifadə nümunəsi:
 * const trie = new Trie();
 * trie.insert("apple");
 * trie.search("apple"); // true
 * trie.search("app"); // false
 * trie.startsWith("app"); // true
 * trie.insert("app");
 * trie.search("app"); // true
 */
class Trie {
  constructor() {
    // Həlliniz
  }
  
  // Metodları yazın: insert, search, startsWith
}

/*
 * --------------Tapşırıq 4------------5  : N-Vəzir məsələsini həll edin
 * 
 * Təsvir: N-Vəzir məsələsi - n × n şahmat taxtasında n vəziri elə yerləşdirməkdir ki,
 * onlar bir-birini təhdid etməsinlər. Şahmatda vəzir üfüqi, şaquli və diaqonal
 * istiqamətlərdə hərəkət edə bilir.
 * 
 * Bu məsələ backtracking alqoritmindən istifadə edərək həll olunur. Backtracking -
 * problemlərin həlli zamanı bütün mümkün variantları yoxlayıb, lazım gəldikdə
 * geri qayıdıb digər variantları sınaqdan keçirmək metodudur.
 * 
 * Giriş: n - şahmat taxtasının ölçüsü (n × n) və vəzirlərin sayı
 * Çıxış: Vəzirlərin bütün mümkün yerləşmə variantları. Hər bir həll n × n matris şəklində
 * təsvir olunur, burada 'Q' vəzirin olduğu yeri, '.' isə boş xanaları göstərir.
 * 
 * İstifadə nümunəsi:
 * solveNQueens(4);
 * // Nəticə:
 * // [
 * //   [".Q..",  // Həll 1
 * //    "...Q",
 * //    "Q...",
 * //    "..Q."],
 * //
 * //   ["..Q.",  // Həll 2
 * //    "Q...",
 * //    "...Q",
 * //    ".Q.."]
 * // ]
 */
function solveNQueens(n) {
  // Həlliniz
}

/*
 * --------------Tapşırıq 4------------6  : Redaktə məsafəsi (Levenshtein məsafəsi)
 * 
 * Təsvir: Redaktə məsafəsi (Levenshtein məsafəsi) - bir mətni digərinə çevirmək üçün
 * lazım olan minimum əməliyyat sayını ölçür. Mümkün əməliyyatlar:
 * - Hərfin əlavə edilməsi
 * - Hərfin silinməsi
 * - Hərfin dəyişdirilməsi
 * 
 * Bu məsələ dinamik proqramlaşdırma (dynamic programming) ilə həll olunur və
 * bir çox mətn analizi, təbii dil emalı və bioinformatika sahələrində tətbiq olunur.
 * 
 * Giriş: İki mətn. Məsələn: "kitten" və "sitting"
 * Çıxış: Minimum əməliyyat sayı. Yuxarıdakı nümunə üçün: 3
 * 
 * İstifadə nümunəsi:
 * editDistance("kitten", "sitting"); // 3 (kitten -> sitten -> sittin -> sitting)
 * editDistance("sunday", "saturday"); // 3 (sunday -> sunady -> saturdy -> saturday)
 * editDistance("abc", "abc"); // 0
 */
function editDistance(str1, str2) {
  // Həlliniz
}

/*
 * --------------Tapşırıq 4------------7  : Minimum Yığın (Min Heap) yaradın
 * 
 * Təsvir: Minimum Yığın (Min Heap) - xüsusi növ ikili ağacdır, burada hər bir düyünün
 * dəyəri onun uşaqlarının dəyərlərindən kiçik və ya onlara bərabərdir. Bunun nəticəsində,
 * ağacın kökü (root) ən kiçik elementdir.
 * 
 * Min Heap-də həyata keçirilməli olan əsas əməliyyatlar:
 * - insert(value): Yığına yeni element əlavə edir
 * - extractMin(): Ən kiçik elementi (kökü) çıxarıb qaytarır
 * - heapify(index): Yığını düzgün formada saxlamaq üçün istifadə olunur
 * 
 * Min Heap prioritet növbələri (priority queues), planlaşdırma alqoritmləri və 
 * Dijkstra alqoritminin effektiv implementasiyası üçün istifadə olunur.
 * 
 * Giriş/Çıxış: MinHeap sinfi və onun metodları
 * 
 * İstifadə nümunəsi:
 * const minHeap = new MinHeap();
 * minHeap.insert(3);
 * minHeap.insert(1);
 * minHeap.insert(5);
 * minHeap.extractMin(); // 1
 * minHeap.extractMin(); // 3
 */
class MinHeap {
  constructor() {
    // Həlliniz
  }
  
  // Metodları yazın: insert, extractMin, heapify
}

/*
 * --------------Tapşırıq 4------------8  : Çanta məsələsini (Knapsack) həll edin
 * 
 * Təsvir: Çanta məsələsi (Knapsack Problem) - verilmiş çəki məhdudiyyəti daxilində,
 * maksimum dəyərə malik əşyaların seçilməsi problemidir. Hər əşyanın çəkisi və dəyəri var,
 * çantanın isə maksimum tutumu (capacity) var.
 * 
 * Bu məsələni iki versiyası var:
 * - 0/1 Knapsack: Hər əşyadan ya bir dənə götürülür, ya da heç götürülmür
 * - Fractional Knapsack: Əşyaların hissələri götürülə bilər
 * 
 * Bu məsələdə 0/1 Knapsack versiyasını həll etməlisiniz, yəni hər əşyadan ya tam olaraq
 * bir dənə götürülür, ya da heç götürülmür. Bu məsələ dinamik proqramlaşdırma (dynamic
 * programming) ilə həll olunur.
 * 
 * Giriş: 
 * - weights: Əşyaların çəkiləri massivi
 * - values: Əşyaların dəyərləri massivi
 * - capacity: Çantanın maksimum tutumu
 * 
 * Çıxış: Çantaya yerləşdirilə bilən maksimum dəyər
 * 
 * İstifadə nümunəsi:
 * knapsack([2, 3, 4, 5], [3, 4, 5, 6], 5); // 7 (2 və 3 çəkili əşyalar, dəyərləri 3 + 4 = 7)
 * knapsack([1, 2, 3], [10, 15, 40], 6); // 65 (bütün əşyalar sığır)
 */
function knapsack(weights, values, capacity) {
  // Həlliniz
}

/*
 * --------------Tapşırıq 4------------9  : Topoloji Sıralama (Topological Sorting)
 * 
 * Təsvir: Topoloji Sıralama - istiqamətlənmiş dövrsüz qrafın (DAG - Directed Acyclic Graph)
 * təpələrinin elə xətti sıralanmasıdır ki, hər bir til (u, v) üçün u təpəsi sıralamada v təpəsindən
 * əvvəl gəlir.
 * 
 * Topoloji sıralama yalnız dövrsüz qraflar üçün mümkündür. Əgər qrafda dövr varsa,
 * topoloji sıralama mövcud deyil.
 * 
 * Topoloji sıralama DFS (Depth-First Search) və ya Kahn alqoritmi ilə həyata keçirilə bilər.
 * DFS yanaşmasında, dərinlik əsaslı axtarış aparılır və təpələr bitirmə vaxtlarına (finishing time)
 * görə tərs sıralanır.
 * 
 * Topoloji sıralama kurs planlaması, task scheduling və data preprocessing kimi sahələrdə
 * geniş tətbiq olunur.
 * 
 * Giriş: İstiqamətlənmiş dövrsüz qraf (adjacency list formatında)
 * Çıxış: Topoloji sıralanmış təpələr massivi
 * 
 * İstifadə nümunəsi:
 * const graph = {
 *   'A': ['C'],
 *   'B': ['C', 'D'],
 *   'C': ['E'],
 *   'D': ['F'],
 *   'E': ['F', 'H'],
 *   'F': ['G'],
 *   'G': [],
 *   'H': []
 * };
 * topologicalSort(graph); // Mümkün nəticə: ['B', 'A', 'D', 'C', 'E', 'F', 'H', 'G']
 */
function topologicalSort(graph) {
  // Həlliniz
}

/*
 * --------------Tapşırıq 5------------0  : Heş Cədvəl (Hash Table) yaradın
 * 
 * Təsvir: Heş Cədvəl (Hash Table) - açar (key) və dəyər (value) cütlərini saxlayan data
 * strukturudur. Heş funksiyası (hash function) açarı dəyərin saxlanıldığı indeksə çevirir.
 * 
 * Heş Cədvəldə həyata keçirilməli olan əsas əməliyyatlar:
 * - set(key, value): Açar-dəyər cütünü əlavə edir və ya mövcud dəyəri yeniləyir
 * - get(key): Açara uyğun dəyəri qaytarır, yoxdursa undefined qaytarır
 * - remove(key): Açar-dəyər cütünü silir
 * - has(key): Açarın mövcud olub-olmadığını yoxlayır
 * 
 * Heş cədvəl kolliziyaları (iki fərqli açarın eyni indeksə düşməsi) həll etmək üçün
 * "ayrılmış zəncirləmə" (separate chaining) və ya "açıq ünvanlama" (open addressing)
 * kimi metodlar istifadə edə bilərsiniz.
 * 
 * Giriş/Çıxış: HashTable sinfi və onun metodları
 * 
 * İstifadə nümunəsi:
 * const hashTable = new HashTable();
 * hashTable.set("name", "John");
 * hashTable.set("age", 30);
 * hashTable.get("name"); // "John"
 * hashTable.has("age"); // true
 * hashTable.remove("name");
 * hashTable.has("name"); // false
 */
class HashTable {
  constructor() {
    // Həlliniz
  }
  
  // Metodları yazın: set, get, remove, has
}