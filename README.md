Too Many Tabs
Seperti halnya banyak orang, Endra suka sekali membuka banyak tabs di browsernya dan hampir tidak pernah menutup tabsnya.

Nah, lama kelamaan tabs yang terbuka banyak sekali dan Endra menjadi kesulitan mencari tab yang ingin dibuka. Ibarat mencari jarum di tumpukan jerami.

Untuk mempermudah kehidupannya - sebagai programmer yang senang berkreasi - Endra membuat sebuah program sederhana untuk mengelompokkan tabs. Tabs dari domain yang sama akan dikelompokkan ke dalam satu tab group.

Bantulah Endra menghitung ada berapa jumlah tab group hasil pengelompokkan tersebut.

Inputs
Baris pertama adalah T jumlah test cases, 1 <= T <= 100
T baris berikutnya adalah URL tabs yang dibuka Endra untuk test case tersebut. Masing-masing baris dipisahkan oleh spasi.
URL tidak diawali protocol (http:// atau https://)
URL dianggap sama jika domain-nya sama persis, i.e. www.ruangguru.com dan ruangguru.com berbeda
Test Set 1
Jumlah tab yang dibuka <= 10
Test Set 2
Jumlah tab yang dibuka <= 1000
Outputs
Untuk masing-masing test case, print satu baris dengan format Case #i: tab_group_count, di mana i adalah nomor test casenya (dimulai dari 1) dan tab_group_count adalah jumlah tab_group
Sample Input
2
www.google.com www.google.com/id www.google.co.id www.google.co.id/account www.ruangguru.com/ruangbelajar roboguru.ruangguru.com roboguru.ruangguru.com/faq
www.google.com www.google.com/id www.google.com/id/account www.google.com/id/account/reset www.google.com/id/account/forget_password
Sample Output
Case #1: 4
Case #2: 1
Explanation
Untuk test case pertama ada 4 tab group:

www.google.com
www.google.co.id
www.ruangguru.com
roboguru.ruangguru.com
Answer Submission Instructions
There is small case and big case score, each has its max score like shown below, your task is to get the highest possible score.
Once you run your code, your source code, small case & big case output will be automatically saved as the answer.
You may run your code as many time as you want (as long as there's still time) until you get the highest possible score.
On some programming languages, we already provide you the template that read the input data, just click Insert Template from top left menu.
The total coding score that we will assess is the sum up of all small and big case scores across all coding tests.
Please make sure the content formatting (symbols, capitalization, space, line break, etc.) of the output result from your code
must match exactly the same like in the sample output shown on the question because it will affect your scoring if you miss even a single space.
Because the data on some small/big case input is huge, so the time to execute your code can be very long. We recommend you to run
the sample case first to make sure your code is right. Note that you will not get any score from sample case, it's just a playground.
You can also edit sample input data from the editor, in case you need to debug/test your code.
