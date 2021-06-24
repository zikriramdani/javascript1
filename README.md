## https://zikriramdani.github.io/javascript1/

const productData = [<br>
    {<br>
        productId: 1000,<br>
        productName: 'Product 1000'<br>
    },<br>
    {<br>
        productId: 1001,<br>
        productName: 'Product 1001'<br>
    }<br>
];<br><br>
const stockData = [<br>
    {<br>
        productId: 1000,<br>
        locationId: 1,<br>
        stock: 21<br>
    },<br>
    {<br>
        productId: 1000,<br>
        locationId: 2,<br>
        stock: 8<br>
    },<br>
    {<br>
        productId: 1001,<br>
        locationId: 1,<br>
        stock: 4<br>
    },<br>
    {<br>
        productId: 1001,<br>
        locationId: 2,<br>
        stock: 10<br>
    }<br>
];<br><br>
const locationData = [<br>
    {<br>
        locationId: 1,<br>
        locationName: 'Location 1'<br>
    },<br>
    {<br>
        locationId: 2,<br>
        locationName: 'Location 2'<br>
    }<br>
];<br><br>

Diinginkan hasil berikut:

const result = [<br>
    {<br>
        productName: 'Product 1000',<br>
        stock: {<br>
            total: 29,<br>
            detail: [<br>
                {<br>
                    locationName: 'Location 1',<br>
                    stock: 21<br>
                },<br>
                {<br>
                    locationName: 'Location 2',<br>
                    stock: 8<br>
                }<br>
            ]<br>
        }<br>
    },<br>
    {<br>
        productName: 'Product 1001',<br>
        stock: {<br>
            total: 14,<br>
            detail: [<br>
                {<br>
                    locationName: 'Location 1',<br>
                    stock: 4<br>
                },<br>
                {<br>
                    locationName: 'Location 2',<br>
                    stock: 10<br>
                }<br>
            ]<br>
        }<br>
    }<br>
];

Tulis fungsi yang mengembalikan hasil seperti di atas dengan ketentuan:
1. Gunakan bahasa pemrograman JavaScript, Python, PHP, atau pseudo-code
2. Algoritma efisien dan dapat digunakan untuk data yang besar (scalable)
3. Minimalisasi penggunaan built-in functions
4. Tambahkan 1 paragraf penjelasan mengenai solusi yang dipilih, seperti alasan, analisa, keuntungan, kerugian

Cara menjalankan:
1. tarik index.html ke browser
2. klik kanan, pilih inspect lalu buka tab console