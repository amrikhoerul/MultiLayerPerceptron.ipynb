# MultiLayerPerceptron
UAS 
# Multilayer-Perceptron
MLP/Multi Layer Perceptron di Python

Perceptron adalah pengklasifikasi linier — algoritma yang mengklasifikasikan input dengan memisahkan dua kategori dengan garis lurus
garis. Input biasanya berupa vektor fitur x dikalikan dengan bobot w dan ditambahkan ke bias b: y = w * x + b.

Perceptron menghasilkan output tunggal berdasarkan beberapa input bernilai nyata dengan membentuk kombinasi linier menggunakan input
bobot (dan terkadang melewati output melalui fungsi aktivasi non-linear).

MLP dapat dianggap sebagai jaringan saraf tiruan yang dalam. Ini terdiri dari lebih dari satu perceptron.
Mereka terdiri dari layer input untuk menerima sinyal, layer output yang membuat keputusan atau prediksi tentang
input, dan di antara keduanya, sejumlah layer tersembunyi yang merupakan mesin komputasi MLP yang sebenarnya.

multilayer perceptron berlatih pada satu set pasangan input-output dan belajar untuk memodelkan korelasi (atau ketergantungan) antara
input dan output tersebut. training melibatkan penyesuaian parameter, atau bobot dan bias, dari model secara berurutan
untuk meminimalkan kesalahan. Backpropagation digunakan untuk membuat penyesuaian bobot dan bias tersebut relatif terhadap kesalahan, dan kesalahan
itu sendiri dapat diukur dengan berbagai cara, termasuk dengan root mean squared error (RMSE).

Jaringan feedforward seperti MLP sama seperti ping-pong: mereka terutama terlibat dalam dua constant, back and
forth (maju dan mundur):

. Pada lintasan maju, aliran sinyal bergerak dari layer input melalui layer tersembunyi ke layer output, dan
keputusan layer output diukur terhadap label kebenaran dasar;

. Dalam lintasan mundur, menggunakan backpropagation dan aturan rantai kalkulus, turunan parsial dari fungsi kesalahan error
mengenai berbagai bobot dan bias yang disebarkan kembali melalui MLP. Tindakan diferensiasi itu memberi kita
gradien, atau lanskap kesalahan, di mana parameter dapat disesuaikan saat mereka memindahkan MLP satu langkah lebih dekat ke
kesalahan minimal. (ini dapat dilakukan dengan algoritma optimasi berbasis gradien seperti penurunan gradien stokastik).

Jaringan terus memainkan permainan ping-pong itu sampai kesalahannya tidak berkurang. Keadaan ini dikenal sebagai konvergensi.
