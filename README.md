<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bukti Pemesanan</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #e50909;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            background-color: #0bd872;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(6, 241, 233, 0.877);
        }
        .header {
            text-align: center;
            margin-bottom: 20px;
        }
        .header img {
            max-width: 150px;
            border-radius: 8px;
        }
        .header h2 {
            margin: 10px 0;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-bottom: 20px;
        }
        table, th, td {
            border: 1px solid #f7fbf8;
        }
        th, td {
            padding: 10px;
            text-align: left;
        }
        th {
            background-color: #d1e004;
        }
        td input[type="number"] {
            width: 60px;
            text-align: center;
        }
        .total, .pajak, .tagihan {
            font-weight: bold;
        }
        .total {
            background-color: #efff12;
        }
        .payment-method {
            margin-bottom: 20px;
        }
        .payment-method label {
            display: block;
            margin-bottom: 5px;
        }
        .footer {
            text-align: center;
            margin-top: 20px;
        }
    </style>
</head>
<body>

<div class="container">
    <div class="header">
        <img src="WhatsApp Image 2024-09-09 at 13.47.40.jpeg" alt="Logo Restaurant">
        <h2>Bukti Pemesanan</h2>
    </div>

    <table>
        <tr>
            <td><strong>Nama Pelayan:</strong> Saddam </td>
            <td><strong>Tanggal Pemesanan:</strong> <input type="date"></td>
        </tr>
        <tr>
            <td><strong>Nama Pemesan:</strong> Vean </td>
            <td><strong>Alamat Pemesan:</strong> Jl. Pangeran Hidayatullah no 88 </td>
        </tr>
    </table>

    <table>
        <thead>
            <tr>
                <th>Nama Menu</th>
                <th>Jumlah</th>
                <th>Harga Satuan</th>
                <th>Total Harga</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>
                    <img src="WhatsApp Image 2024-09-09 at 13.47.40 (1).jpeg" alt="Nasi Goreng Spesial" width="50"><br>
                    Nasi Goreng Spesial
                </td>
                <td><input type="number" value="1" size="1"> Porsi</td>
                <td>Rp 25.000</td>
                <td>Rp 25.000</td>
            </tr>
            <tr>
                <td>
                    <img src="WhatsApp Image 2024-09-09 at 13.47.40 (2).jpeg" alt="Es Teh Manis" width="50"><br>
                    Es Teh Manis
                </td>
                <td><input type="number" value="1" size="1"> Gelas</td>
                <td>Rp 5.000</td>
                <td>Rp 5.000</td>
            </tr>
        </tbody>
        <tfoot>
            <tr>
                <td colspan="3" class="total">Total Pesanan</td>
                <td>Rp 30.000</td>
            </tr>
            <tr>
                <td colspan="3" class="pajak">Pajak</td>
                <td>Rp 2.000</td>
            </tr>
            <tr>
                <td colspan="3" class="tagihan">Total Tagihan</td>
                <td>Rp 32.000</td>
            </tr>
        </tfoot>
    </table>

    <div class="payment-method">
        <p>Metode Pembayaran:</p>
        <label><input type="radio" name="payment" value="BCA"> Bank BCA</label>
        <label><input type="radio" name="payment" value="BRI"> Bank BRI</label>
        <label><input type="radio" name="payment" value="OVO"> OVO</label>
        <label><input type="radio" name="payment" value="GoPay"> GoPay</label>
    </div>

    <div class="footer">
        <p><strong>Nama:</strong> Nor hidayat </p>
        <p><strong>NIM:</strong> 2109106144 </p>
        <p><strong>Praktikum Web:</strong> Posttest 2</p>
    </div>
</div>

</body>
</html>
