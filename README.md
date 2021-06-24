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

const result = [
    {
        productName: 'Product 1000',
        stock: {
            total: 29,
            detail: [
                {
                    locationName: 'Location 1',
                    stock: 21
                },
                {
                    locationName: 'Location 2',
                    stock: 8
                }
            ]
        }
    },
    {
        productName: 'Product 1001',
        stock: {
            total: 14,
            detail: [
                {
                    locationName: 'Location 1',
                    stock: 4
                },
                {
                    locationName: 'Location 2',
                    stock: 10
                }
            ]
        }
    }
];

Tulis fungsi yang mengembalikan hasil seperti di atas dengan ketentuan:
1. Gunakan bahasa pemrograman JavaScript, Python, PHP, atau pseudo-code
2. Algoritma efisien dan dapat digunakan untuk data yang besar (scalable)
3. Minimalisasi penggunaan built-in functions
4. Tambahkan 1 paragraf penjelasan mengenai solusi yang dipilih, seperti alasan, analisa, keuntungan, kerugian