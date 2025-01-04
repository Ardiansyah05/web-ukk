<template>
    <div class="container">
        <div class="header1 bg-primary">
            <h1>Kompetensi Keahlian</h1>
        </div>
        <div class="grid">
            <div class="card">
                <i>&#128187;</i>
                <h2>Teknik Komputer dan Jaringan</h2>
                <ul>
                    <li>Bengkel TKJ</li>
                    <li>Network Simulator</li>
                    <li>Techno Park</li>
                    <li>Dll</li>
                </ul>
            </div>
            <div class="card">
                <i>&#128247;</i>
                <h2>Desain Komunikasi Visual</h2>
                <ul>
                    <li>Bengkel DKV</li>
                    <li>Unit Produksi</li>
                    <li>Techno Park</li>
                    <li>Dll</li>
                </ul>
            </div>
            <div class="card">
                <i>&#128187;</i>
                <h2>Rekayasa Perangkat Lunak</h2>
                <ul>
                    <li>Laboratorium Komputer</li>
                    <li>Computer Server</li>
                    <li>Techno Park</li>
                    <li>Dll</li>
                </ul>
            </div>
            <div class="card">
                <i>&#128295;</i>
                <h2>Teknik Otomasi Industri</h2>
                <ul>
                    <li>Bengkel TOI</li>
                    <li>Unit Produksi</li>
                    <li>Techno Park</li>
                    <li>Dll</li>
                </ul>
            </div>
            <div class="card">
                <i>&#128736;</i>
                <h2>Teknik dan Bisnis Sepeda Motor</h2>
                <ul>
                    <li>Bengkel TBSM</li>
                    <li>Unit Produksi</li>
                    <li>Techno Park</li>
                    <li>Dll</li>
                </ul>
            </div>
        </div>
    </div>
</template>

<style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background: #fff;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        .header1 {
            background: #0099ff;
            color: #ffffff;
            padding: 10px 20px;
            text-align: center;
            border-radius: 5px 5px 0 0;
        }
        .header h1 {
            margin: 0;
            font-size: 24px;
        }
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        .card {
            background: #f9f9f9;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .card h2 {
            margin-bottom: 15px;
            font-size: 18px;
        }
        .card ul {
            list-style: none;
            padding: 0;
            margin: 0;
            text-align: left;
        }
        .card ul li {
            margin: 5px 0;
        }
        .card i {
            font-size: 40px;
            margin-bottom: 10px;
            display: block;
            color: #333;
        }
    </style>