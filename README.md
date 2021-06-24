## https://zikriramdani.github.io/javascript1/

const productData = [
    {
        productId: 1000,
        productName: 'Product 1000'
    },
    {
        productId: 1001,
        productName: 'Product 1001'
    }
];
const stockData = [
    {
        productId: 1000,
        locationId: 1,
        stock: 21
    },
    {
        productId: 1000,
        locationId: 2,
        stock: 8
    },
    {
        productId: 1001,
        locationId: 1,
        stock: 4
    },
    {
        productId: 1001,
        locationId: 2,
        stock: 10
    }
];
const locationData = [
    {
        locationId: 1,
        locationName: 'Location 1'
    },
    {
        locationId: 2,
        locationName: 'Location 2'
    }
];

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

## Tulis fungsi yang mengembalikan hasil seperti di atas dengan ketentuan:
1. Gunakan bahasa pemrograman JavaScript, Python, PHP, atau pseudo-code
2. Algoritma efisien dan dapat digunakan untuk data yang besar (scalable)
3. Minimalisasi penggunaan built-in functions
4. Tambahkan 1 paragraf penjelasan mengenai solusi yang dipilih, seperti alasan, analisa, keuntungan, kerugian

## Cara menjalankan:
1. tarik index.html ke browser
2. klik kanan, pilih inspect lalu buka tab console

## Hasil berikut:

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