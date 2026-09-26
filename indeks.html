<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hans Order & Financial Management System</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        darkbg: '#121212',
                        darkcard: '#1e1e1e',
                        darkinput: '#2a2a2a',
                        fireRed: '#dc2626',
                        fireOrange: '#f97316',
                        fireGold: '#eab308'
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <style>
        ::-webkit-scrollbar {
            width: 8px;
            height: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #121212;
        }
        ::-webkit-scrollbar-thumb {
            background: #333;
            border-radius: 4px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #dc2626;
        }
        .fire-gradient-text {
            background: linear-gradient(135deg, #ef4444, #f97316, #eab308);
            background-clip: text;
            -webkit-background-clip: text;
            color: transparent;
            -webkit-text-fill-color: transparent;
        }
        .fire-border-glow {
            box-shadow: 0 0 15px rgba(220, 38, 38, 0.25);
        }

        @media print {
            body * {
                visibility: hidden;
            }
            #detailModal, #detailModal * {
                visibility: visible;
            }
            #detailModal {
                position: absolute;
                left: 0;
                top: 0;
                width: 100%;
                background: white !important;
                color: black !important;
            }
            .no-print {
                display: none !important;
            }
        }
    </style>
</head>
<body class="bg-darkbg text-gray-200 min-h-screen font-sans flex flex-col antialiased">

    <!-- LOGIN SCREEN -->
    <div id="loginPage" class="fixed inset-0 z-50 flex items-center justify-center bg-darkbg px-4">
        <div class="bg-darkcard border border-gray-800 rounded-2xl p-8 max-w-md w-full shadow-2xl fire-border-glow text-center">
            <div class="relative w-28 h-28 mx-auto mb-4 rounded-full p-1 bg-gradient-to-tr from-red-600 via-orange-500 to-yellow-400 shadow-lg flex items-center justify-center">
                <div class="w-full h-full bg-darkbg rounded-full flex flex-col items-center justify-center p-2 border border-black/50">
                    <span class="text-3xl font-black tracking-wider text-red-500 italic">Hans</span>
                    <span class="text-[9px] uppercase tracking-widest text-gray-400 -mt-1 font-semibold">Sublim & Printing</span>
                </div>
            </div>

            <h2 class="text-2xl font-bold fire-gradient-text mb-1">Hans Production</h2>
            <p class="text-xs text-gray-400 mb-6">Manajemen Order & Keuangan Harian</p>

            <form id="loginForm" class="space-y-4 text-left">
                <div>
                    <label class="block text-xs text-gray-400 uppercase tracking-wider mb-1">Username</label>
                    <div class="relative">
                        <span class="absolute inset-y-0 left-0 pl-3 flex items-center text-gray-500">
                            <i class="fas fa-user"></i>
                        </span>
                        <input type="text" id="loginUsername" value="admin" required class="w-full bg-darkinput border border-gray-700 rounded-lg pl-10 pr-4 py-2 text-sm text-white focus:outline-none focus:border-red-500 transition">
                    </div>
                </div>
                <div>
                    <label class="block text-xs text-gray-400 uppercase tracking-wider mb-1">Password</label>
                    <div class="relative">
                        <span class="absolute inset-y-0 left-0 pl-3 flex items-center text-gray-500">
                            <i class="fas fa-lock"></i>
                        </span>
                        <input type="password" id="loginPassword" value="123456" required class="w-full bg-darkinput border border-gray-700 rounded-lg pl-10 pr-4 py-2 text-sm text-white focus:outline-none focus:border-red-500 transition">
                    </div>
                </div>

                <div id="loginError" class="hidden text-xs text-red-400 bg-red-950/40 border border-red-800/50 p-2 rounded text-center">
                    Username atau password salah!
                </div>

                <button type="submit" class="w-full bg-gradient-to-r from-red-600 to-orange-600 hover:from-red-500 hover:to-orange-500 text-white font-semibold py-2.5 rounded-lg shadow-md transition transform active:scale-[0.99]">
                    <i class="fas fa-sign-in-alt mr-2"></i> Masuk Aplikasi
                </button>
            </form>
            <p class="text-[11px] text-gray-500 mt-6">Default Login: <b>admin</b> / <b>123456</b></p>
        </div>
    </div>

    <!-- MAIN DASHBOARD APP -->
    <div id="appContainer" class="hidden flex-1 flex flex-col">
        <!-- HEADER / NAVIGATION -->
        <header class="bg-darkcard border-b border-gray-800 sticky top-0 z-30 shadow-md">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-16 flex items-center justify-between">
                <div class="flex items-center space-x-6">
                    <div class="flex items-center space-x-3">
                        <div class="w-10 h-10 rounded-full bg-gradient-to-tr from-red-600 to-yellow-500 p-0.5 flex items-center justify-center">
                            <div class="w-full h-full bg-darkbg rounded-full flex flex-col items-center justify-center p-1">
                                <span class="text-xs font-black text-red-500 italic">Hans</span>
                            </div>
                        </div>
                        <div>
                            <h1 class="text-lg font-bold tracking-wide text-white flex items-center">
                                Hans <span class="ml-1 text-xs text-red-500 font-semibold px-2 py-0.5 rounded bg-red-950/60 border border-red-800/40">Production</span>
                            </h1>
                            <p class="text-[10px] text-gray-400">Order & Financial Tracking</p>
                        </div>
                    </div>

                    <!-- TAB NAVIGATION -->
                    <nav class="hidden md:flex space-x-2">
                        <button id="tabOrdersBtn" onclick="switchTab('orders')" class="px-3 py-1.5 rounded-lg text-xs font-semibold bg-red-600 text-white transition flex items-center space-x-1">
                            <i class="fas fa-boxes"></i>
                            <span>Daftar Order</span>
                        </button>
                        <button id="tabFinanceBtn" onclick="switchTab('finance')" class="px-3 py-1.5 rounded-lg text-xs font-semibold bg-darkbg text-gray-400 hover:text-white transition flex items-center space-x-1 border border-gray-800">
                            <i class="fas fa-file-invoice-dollar text-green-400"></i>
                            <span>Keuangan Harian</span>
                        </button>
                    </nav>
                </div>

                <div class="flex items-center space-x-4">
                    <button id="logoutBtn" class="bg-gray-800 hover:bg-red-900/60 text-gray-300 hover:text-red-300 text-xs px-3 py-2 rounded-lg border border-gray-700 transition flex items-center space-x-1">
                        <i class="fas fa-power-off"></i>
                        <span class="hidden sm:inline">Keluar</span>
                    </button>
                </div>
            </div>
        </header>

        <!-- VIEW 1: MANAGEMENT ORDER -->
        <main id="ordersView" class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-6 flex-1 w-full space-y-6">
            <!-- STATS SUMMARY CARDS -->
            <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
                <div class="bg-darkcard border border-gray-800 p-4 rounded-xl flex items-center space-x-4">
                    <div class="p-3 bg-red-950/50 text-red-500 rounded-lg border border-red-900/40">
                        <i class="fas fa-box text-xl"></i>
                    </div>
                    <div>
                        <p class="text-xs text-gray-400">Total Order</p>
                        <h3 id="statTotalOrders" class="text-xl font-bold text-white">0</h3>
                    </div>
                </div>
                <div class="bg-darkcard border border-gray-800 p-4 rounded-xl flex items-center space-x-4">
                    <div class="p-3 bg-yellow-950/50 text-yellow-500 rounded-lg border border-yellow-900/40">
                        <i class="fas fa-spinner text-xl"></i>
                    </div>
                    <div>
                        <p class="text-xs text-gray-400">Proses Produksi</p>
                        <h3 id="statProcessingOrders" class="text-xl font-bold text-white">0</h3>
                    </div>
                </div>
                <div class="bg-darkcard border border-gray-800 p-4 rounded-xl flex items-center space-x-4">
                    <div class="p-3 bg-green-950/50 text-green-500 rounded-lg border border-green-900/40">
                        <i class="fas fa-check-circle text-xl"></i>
                    </div>
                    <div>
                        <p class="text-xs text-gray-400">Selesai</p>
                        <h3 id="statCompletedOrders" class="text-xl font-bold text-white">0</h3>
                    </div>
                </div>
                <div class="bg-darkcard border border-gray-800 p-4 rounded-xl flex items-center space-x-4">
                    <div class="p-3 bg-blue-950/50 text-blue-400 rounded-lg border border-blue-900/40">
                        <i class="fas fa-wallet text-xl"></i>
                    </div>
                    <div>
                        <p class="text-xs text-gray-400">Total Omset</p>
                        <h3 id="statTotalRevenue" class="text-base sm:text-lg font-bold text-white">Rp 0</h3>
                    </div>
                </div>
            </div>

            <!-- ACTION BAR & FILTER -->
            <div class="bg-darkcard p-4 rounded-xl border border-gray-800 flex flex-col md:flex-row gap-3 items-center justify-between">
                <div class="relative w-full md:w-80">
                    <span class="absolute inset-y-0 left-0 pl-3 flex items-center text-gray-400">
                        <i class="fas fa-search"></i>
                    </span>
                    <input type="text" id="searchInput" placeholder="Cari nama customer / ID..." class="w-full bg-darkinput border border-gray-700 rounded-lg pl-9 pr-4 py-2 text-sm text-white placeholder-gray-500 focus:outline-none focus:border-red-500">
                </div>

                <div class="flex items-center w-full md:w-auto gap-3">
                    <select id="statusFilter" class="bg-darkinput border border-gray-700 rounded-lg px-3 py-2 text-sm text-gray-200 focus:outline-none focus:border-red-500">
                        <option value="ALL">Semua Status</option>
                        <option value="Pending">Pending</option>
                        <option value="Proses">Dalam Proses</option>
                        <option value="Selesai">Selesai</option>
                    </select>

                    <button id="openNewOrderModal" class="w-full md:w-auto bg-gradient-to-r from-red-600 to-orange-600 hover:from-red-500 hover:to-orange-500 text-white px-4 py-2 rounded-lg text-sm font-semibold transition flex items-center justify-center space-x-2 shadow-md">
                        <i class="fas fa-plus-circle"></i>
                        <span>Tambah Order Baru</span>
                    </button>
                </div>
            </div>

            <!-- DATABASE ORDERS TABLE VIEW -->
            <div class="bg-darkcard rounded-xl border border-gray-800 overflow-hidden shadow-xl">
                <div class="p-4 border-b border-gray-800 flex justify-between items-center">
                    <h2 class="font-bold text-white flex items-center space-x-2">
                        <i class="fas fa-list text-red-500"></i>
                        <span>Database Pesanan Production</span>
                    </h2>
                    <span id="orderCounter" class="text-xs bg-gray-800 text-gray-400 px-2.5 py-1 rounded-full">0 Order</span>
                </div>

                <div class="overflow-x-auto">
                    <table class="w-full text-left border-collapse text-sm">
                        <thead>
                            <tr class="bg-darkbg text-gray-400 border-b border-gray-800 text-xs uppercase">
                                <th class="p-3">Order ID / Desain</th>
                                <th class="p-3">Nama Customer</th>
                                <th class="p-3">Masuk / Deadline</th>
                                <th class="p-3">Total & DP</th>
                                <th class="p-3 text-center">Status Bayar</th>
                                <th class="p-3 text-center">Status Produksi</th>
                                <th class="p-3 text-center">Aksi</th>
                            </tr>
                        </thead>
                        <tbody id="ordersTableBody" class="divide-y divide-gray-800 text-gray-300">
                        </tbody>
                    </table>
                </div>

                <div id="emptyState" class="hidden p-12 text-center">
                    <i class="fas fa-folder-open text-4xl text-gray-600 mb-3"></i>
                    <p class="text-gray-400 text-sm">Belum ada data order yang cocok.</p>
                </div>
            </div>
        </main>

        <!-- VIEW 2: HALAMAN PEMBUKUAN KEUANGAN HARIAN -->
        <main id="financeView" class="hidden max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-6 flex-1 w-full space-y-6">
            <!-- HEADER KEUANGAN & FILTER TANGGAL -->
            <div class="bg-darkcard p-4 rounded-xl border border-gray-800 flex flex-col sm:flex-row justify-between items-center gap-4">
                <div>
                    <h2 class="text-lg font-bold text-white flex items-center space-x-2">
                        <i class="fas fa-cash-register text-green-500"></i>
                        <span>Laporan Pembukuan Keuangan Harian</span>
                    </h2>
                    <p class="text-xs text-gray-400">Ringkasan transaksi DP, pelunasan, dan piutang pelanggan</p>
                </div>
                <div class="flex items-center space-x-2">
                    <label class="text-xs text-gray-400">Pilih Tanggal:</label>
                    <input type="date" id="financeDateFilter" class="bg-darkinput border border-gray-700 rounded-lg px-3 py-1.5 text-xs text-white focus:outline-none focus:border-red-500">
                </div>
            </div>

            <!-- CARDS RINGKASAN KEUANGAN -->
            <div class="grid grid-cols-1 md:grid-cols-4 gap-4">
                <div class="bg-darkcard border border-gray-800 p-4 rounded-xl">
                    <span class="text-xs text-gray-400 block mb-1">Total Pemasukan (DP + Lunas)</span>
                    <h3 id="finTotalReceived" class="text-xl font-bold text-green-400">Rp 0</h3>
                    <span class="text-[10px] text-gray-500">Kas nyata diterima pada tanggal ini</span>
                </div>
                <div class="bg-darkcard border border-gray-800 p-4 rounded-xl">
                    <span class="text-xs text-gray-400 block mb-1">Total DP Diterima</span>
                    <h3 id="finTotalDP" class="text-xl font-bold text-yellow-400">Rp 0</h3>
                    <span class="text-[10px] text-gray-500">Uang muka pesanan masuk</span>
                </div>
                <div class="bg-darkcard border border-gray-800 p-4 rounded-xl">
                    <span class="text-xs text-gray-400 block mb-1">Sisa Piutang / Belum Bayar</span>
                    <h3 id="finTotalUnpaid" class="text-xl font-bold text-red-400">Rp 0</h3>
                    <span class="text-[10px] text-gray-500">Tagihan yang masih menggantung</span>
                </div>
                <div class="bg-darkcard border border-gray-800 p-4 rounded-xl">
                    <span class="text-xs text-gray-400 block mb-1">Potensi Omset Order</span>
                    <h3 id="finTotalTarget" class="text-xl font-bold text-blue-400">Rp 0</h3>
                    <span class="text-[10px] text-gray-500">Nilai total dari order tanggal ini</span>
                </div>
            </div>

            <!-- RINCIAN TRANSAKSI KAS MASUK -->
            <div class="bg-darkcard rounded-xl border border-gray-800 overflow-hidden shadow-xl">
                <div class="p-4 border-b border-gray-800">
                    <h3 class="font-bold text-white text-sm flex items-center space-x-2">
                        <i class="fas fa-file-invoice-dollar text-green-400"></i>
                        <span>Rincian Transaksi Pemasukan Order</span>
                    </h3>
                </div>
                <div class="overflow-x-auto">
                    <table class="w-full text-left border-collapse text-sm">
                        <thead>
                            <tr class="bg-darkbg text-gray-400 border-b border-gray-800 text-xs uppercase">
                                <th class="p-3">ID Order</th>
                                <th class="p-3">Nama Customer</th>
                                <th class="p-3">Total Order</th>
                                <th class="p-3">Uang Muka (DP)</th>
                                <th class="p-3">Sisa Kekurangan</th>
                                <th class="p-3 text-center">Status Bayar</th>
                            </tr>
                        </thead>
                        <tbody id="financeTableBody" class="divide-y divide-gray-800 text-gray-300">
                        </tbody>
                    </table>
                </div>
            </div>
        </main>
    </div>

    <!-- MODAL ADD / EDIT ORDER -->
    <div id="orderModal" class="fixed inset-0 z-50 bg-black/80 backdrop-blur-sm hidden flex items-center justify-center p-4 overflow-y-auto">
        <div class="bg-darkcard border border-gray-800 rounded-2xl w-full max-w-2xl my-8 overflow-hidden shadow-2xl flex flex-col max-h-[90vh]">
            <div class="p-4 bg-darkbg border-b border-gray-800 flex justify-between items-center">
                <h3 id="modalTitle" class="text-lg font-bold text-white flex items-center space-x-2">
                    <i class="fas fa-file-invoice text-red-500"></i>
                    <span>Tambah Pesanan Baru</span>
                </h3>
                <button id="closeOrderModal" class="text-gray-400 hover:text-white p-1">
                    <i class="fas fa-times text-lg"></i>
                </button>
            </div>

            <form id="orderForm" class="p-6 overflow-y-auto space-y-6 flex-1">
                <input type="hidden" id="editOrderId">

                <!-- INFORMASI PEMESAN -->
                <div>
                    <h4 class="text-xs uppercase font-bold text-red-400 tracking-wider mb-3">1. Informasi Pemesan & Waktu</h4>
                    <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
                        <div class="md:col-span-3">
                            <label class="block text-xs text-gray-400 mb-1">Nama Customer *</label>
                            <input type="text" id="inputCustomerName" required placeholder="Contoh: Tim Futsal Garuda / Bpk. Budi" class="w-full bg-darkinput border border-gray-700 rounded-lg px-3 py-2 text-sm text-white focus:outline-none focus:border-red-500">
                        </div>
                        <div>
                            <label class="block text-xs text-gray-400 mb-1">Tanggal Masuk *</label>
                            <input type="date" id="inputDateIn" required class="w-full bg-darkinput border border-gray-700 rounded-lg px-3 py-2 text-sm text-white focus:outline-none focus:border-red-500">
                        </div>
                        <div>
                            <label class="block text-xs text-gray-400 mb-1">Deadline Selesai *</label>
                            <input type="date" id="inputDeadline" required class="w-full bg-darkinput border border-gray-700 rounded-lg px-3 py-2 text-sm text-white focus:outline-none focus:border-red-500">
                        </div>
                        <div>
                            <label class="block text-xs text-gray-400 mb-1">Status Produksi</label>
                            <select id="inputStatus" class="w-full bg-darkinput border border-gray-700 rounded-lg px-3 py-2 text-sm text-white focus:outline-none focus:border-red-500">
                                <option value="Pending">Pending</option>
                                <option value="Proses">Dalam Proses</option>
                                <option value="Selesai">Selesai</option>
                            </select>
                        </div>
                    </div>
                </div>

                <!-- RINCIAN PESANAN DAN HARGA -->
                <div>
                    <h4 class="text-xs uppercase font-bold text-red-400 tracking-wider mb-3">2. Rincian Pakaian & Harga</h4>
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                        <div class="bg-darkbg p-3 rounded-xl border border-gray-800 space-y-2">
                            <span class="text-xs font-semibold text-gray-300 block border-b border-gray-800 pb-1">
                                <i class="fas fa-shirt text-orange-400 mr-1"></i> Lengan Pendek
                            </span>
                            <div class="grid grid-cols-2 gap-2">
                                <div>
                                    <label class="block text-[11px] text-gray-400">Qty (Pcs)</label>
                                    <input type="number" id="qtyShort" min="0" value="0" class="calc-trigger w-full bg-darkinput border border-gray-700 rounded-lg px-3 py-1.5 text-sm text-white focus:outline-none focus:border-red-500">
                                </div>
                                <div>
                                    <label class="block text-[11px] text-gray-400">Harga / Pcs (Rp)</label>
                                    <input type="number" id="priceShort" min="0" value="75000" class="calc-trigger w-full bg-darkinput border border-gray-700 rounded-lg px-3 py-1.5 text-sm text-white focus:outline-none focus:border-red-500">
                                </div>
                            </div>
                        </div>

                        <div class="bg-darkbg p-3 rounded-xl border border-gray-800 space-y-2">
                            <span class="text-xs font-semibold text-gray-300 block border-b border-gray-800 pb-1">
                                <i class="fas fa-shirt text-yellow-400 mr-1"></i> Lengan Panjang
                            </span>
                            <div class="grid grid-cols-2 gap-2">
                                <div>
                                    <label class="block text-[11px] text-gray-400">Qty (Pcs)</label>
                                    <input type="number" id="qtyLong" min="0" value="0" class="calc-trigger w-full bg-darkinput border border-gray-700 rounded-lg px-3 py-1.5 text-sm text-white focus:outline-none focus:border-red-500">
                                </div>
                                <div>
                                    <label class="block text-[11px] text-gray-400">Harga / Pcs (Rp)</label>
                                    <input type="number" id="priceLong" min="0" value="85000" class="calc-trigger w-full bg-darkinput border border-gray-700 rounded-lg px-3 py-1.5 text-sm text-white focus:outline-none focus:border-red-500">
                                </div>
                            </div>
                        </div>

                        <div class="md:col-span-2 bg-darkbg p-3 rounded-xl border border-gray-800 space-y-2">
                            <span class="text-xs font-semibold text-gray-300 block border-b border-gray-800 pb-1">
                                <i class="fas fa-expand-alt text-red-400 mr-1"></i> Cas Ukuran Jumbo (XXL, 3XL, dst)
                            </span>
                            <div class="grid grid-cols-1 md:grid-cols-2 gap-2">
                                <div>
                                    <label class="block text-[11px] text-gray-400">Catatan Ukuran Extra</label>
                                    <input type="text" id="sizeExtraNote" placeholder="Contoh: XXL 2pcs, 3XL 1pc" class="w-full bg-darkinput border border-gray-700 rounded-lg px-3 py-1.5 text-sm text-white focus:outline-none focus:border-red-500">
                                </div>
                                <div>
                                    <label class="block text-[11px] text-gray-400">Total Cas Tambahan (Rp)</label>
                                    <input type="number" id="priceSizeCharge" min="0" value="0" class="calc-trigger w-full bg-darkinput border border-gray-700 rounded-lg px-3 py-1.5 text-sm text-white focus:outline-none focus:border-red-500">
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- FITUR PEMBAYARAN DP & LUNAS -->
                <div>
                    <h4 class="text-xs uppercase font-bold text-red-400 tracking-wider mb-3">3. Pembayaran & Down Payment (DP)</h4>
                    <div class="bg-darkbg p-4 rounded-xl border border-gray-800 space-y-3">
                        <div class="grid grid-cols-1 md:grid-cols-2 gap-3">
                            <div>
                                <label class="block text-xs text-gray-400 mb-1">Jumlah DP Diterima (Rp)</label>
                                <input type="number" id="inputDP" min="0" value="0" class="calc-trigger w-full bg-darkinput border border-gray-700 rounded-lg px-3 py-2 text-sm text-white focus:outline-none focus:border-red-500">
                            </div>
                            <div>
                                <label class="block text-xs text-gray-400 mb-1">Sisa Pembayaran (Rp)</label>
                                <input type="text" id="displayRemaining" readonly value="Rp 0" class="w-full bg-gray-900 border border-gray-800 rounded-lg px-3 py-2 text-sm font-bold text-red-400">
                            </div>
                        </div>
                    </div>
                </div>

                <!-- TOTAL RINGKASAN HARGA -->
                <div class="bg-gradient-to-r from-red-950/40 via-darkbg to-darkbg border border-red-900/50 p-4 rounded-xl flex items-center justify-between">
                    <div>
                        <span class="text-xs text-gray-400 block">Total Tagihan:</span>
                        <span id="calculatedTotalDisplay" class="text-xl font-bold text-yellow-400">Rp 0</span>
                    </div>
                    <div class="text-right text-xs text-gray-400">
                        Total Pcs: <span id="calculatedQtyDisplay" class="text-white font-bold">0</span> Pcs
                    </div>
                </div>

                <!-- UPLOAD GAMBAR DESAIN -->
                <div>
                    <h4 class="text-xs uppercase font-bold text-red-400 tracking-wider mb-3">4. Foto Desain Order Produksi</h4>
                    <div class="flex flex-col sm:flex-row items-center gap-4">
                        <div id="imagePreviewContainer" class="w-32 h-32 bg-darkbg border-2 border-dashed border-gray-700 rounded-xl flex items-center justify-center overflow-hidden shrink-0 relative">
                            <span id="noImgText" class="text-xs text-gray-500 text-center p-2">Belum ada gambar</span>
                            <img id="imagePreview" class="hidden w-full h-full object-cover">
                        </div>
                        <div class="flex-1 w-full space-y-2">
                            <label class="block text-xs text-gray-400">Upload Desain Jersey</label>
                            <input type="file" id="inputImageFile" accept="image/*" class="block w-full text-xs text-gray-400 file:mr-4 file:py-2 file:px-4 file:rounded-lg file:border-0 file:text-xs file:font-semibold file:bg-red-950/60 file:text-red-300 hover:file:bg-red-900 cursor-pointer border border-gray-800 rounded-lg bg-darkbg">
                        </div>
                    </div>
                </div>

                <div class="pt-4 border-t border-gray-800 flex justify-end space-x-3">
                    <button type="button" id="cancelOrderModal" class="px-4 py-2 bg-gray-800 hover:bg-gray-700 text-gray-300 rounded-lg text-sm transition">Batal</button>
                    <button type="submit" class="px-6 py-2 bg-gradient-to-r from-red-600 to-orange-600 hover:from-red-500 hover:to-orange-500 text-white font-semibold rounded-lg text-sm shadow-lg transition">Simpan Pesanan</button>
                </div>
            </form>
        </div>
    </div>

    <!-- DETAIL MODAL / SPK NOTA -->
    <div id="detailModal" class="fixed inset-0 z-50 bg-black/80 backdrop-blur-sm hidden flex items-center justify-center p-4">
        <div class="bg-darkcard border border-gray-800 rounded-2xl w-full max-w-lg overflow-hidden shadow-2xl flex flex-col">
            <div class="p-4 bg-darkbg border-b border-gray-800 flex justify-between items-center no-print">
                <h3 class="text-lg font-bold text-white flex items-center space-x-2">
                    <i class="fas fa-info-circle text-red-500"></i>
                    <span>Rincian Order & SPK Hans Printing</span>
                </h3>
                <button id="closeDetailModal" class="text-gray-400 hover:text-white">
                    <i class="fas fa-times text-lg"></i>
                </button>
            </div>

            <div id="detailContent" class="p-6 space-y-4 overflow-y-auto max-h-[80vh]">
            </div>

            <div class="p-4 bg-darkbg border-t border-gray-800 flex justify-between items-center no-print">
                <button id="printOrderBtn" class="bg-gray-800 hover:bg-gray-700 text-gray-300 text-xs px-3 py-2 rounded-lg border border-gray-700 flex items-center space-x-1">
                    <i class="fas fa-print"></i>
                    <span>Cetak Nota / SPK</span>
                </button>
                <button id="closeDetailBtn" class="bg-red-600 hover:bg-red-500 text-white text-xs px-4 py-2 rounded-lg font-semibold">Tutup</button>
            </div>
        </div>
    </div>

    <script>
        const INITIAL_ORDERS = [
            {
                id: "ORD-1001",
                customerName: "Tim Futsal FC Renegade",
                dateIn: "2026-03-26",
                deadline: "2026-03-30",
                qtyShort: 12,
                priceShort: 75000,
                qtyLong: 3,
                priceLong: 85000,
                sizeExtraNote: "XXL 2Pcs",
                priceSizeCharge: 20000,
                totalPrice: 1175000,
                dpAmount: 500000,
                totalQty: 15,
                status: "Proses",
                image: "https://placehold.co/400x400/2a2a2a/dc2626?text=Jersey+Renegade"
            }
        ];

        let orders = [];
        let currentBase64Image = "";

        const loginPage = document.getElementById('loginPage');
        const loginForm = document.getElementById('loginForm');
        const loginError = document.getElementById('loginError');
        const appContainer = document.getElementById('appContainer');
        const logoutBtn = document.getElementById('logoutBtn');

        const ordersView = document.getElementById('ordersView');
        const financeView = document.getElementById('financeView');
        const ordersTableBody = document.getElementById('ordersTableBody');
        const financeTableBody = document.getElementById('financeTableBody');
        const searchInput = document.getElementById('searchInput');
        const statusFilter = document.getElementById('statusFilter');

        const orderModal = document.getElementById('orderModal');
        const openNewOrderModal = document.getElementById('openNewOrderModal');
        const closeOrderModal = document.getElementById('closeOrderModal');
        const cancelOrderModal = document.getElementById('cancelOrderModal');
        const orderForm = document.getElementById('orderForm');

        const inputImageFile = document.getElementById('inputImageFile');
        const imagePreview = document.getElementById('imagePreview');
        const noImgText = document.getElementById('noImgText');

        const detailModal = document.getElementById('detailModal');
        const closeDetailModal = document.getElementById('closeDetailModal');
        const closeDetailBtn = document.getElementById('closeDetailBtn');
        const detailContent = document.getElementById('detailContent');
        const printOrderBtn = document.getElementById('printOrderBtn');
        const financeDateFilter = document.getElementById('financeDateFilter');

        window.addEventListener('DOMContentLoaded', () => {
            loadDatabase();
            setupCalculators();
            
            // Set default tanggal filter keuangan ke hari ini
            const today = new Date().toISOString().split('T')[0];
            financeDateFilter.value = today;

            if (sessionStorage.getItem('hans_auth') === 'true') {
                showDashboard();
            }
        });

        // Tab Switching Logic
        window.switchTab = function(tab) {
            const btnOrders = document.getElementById('tabOrdersBtn');
            const btnFinance = document.getElementById('tabFinanceBtn');

            if (tab === 'orders') {
                ordersView.classList.remove('hidden');
                financeView.classList.add('hidden');
                btnOrders.className = "px-3 py-1.5 rounded-lg text-xs font-semibold bg-red-600 text-white transition flex items-center space-x-1";
                btnFinance.className = "px-3 py-1.5 rounded-lg text-xs font-semibold bg-darkbg text-gray-400 hover:text-white transition flex items-center space-x-1 border border-gray-800";
            } else {
                ordersView.classList.add('hidden');
                financeView.classList.remove('hidden');
                btnFinance.className = "px-3 py-1.5 rounded-lg text-xs font-semibold bg-red-600 text-white transition flex items-center space-x-1";
                btnOrders.className = "px-3 py-1.5 rounded-lg text-xs font-semibold bg-darkbg text-gray-400 hover:text-white transition flex items-center space-x-1 border border-gray-800";
                renderFinanceTable();
            }
        };

        // Login System
        loginForm.addEventListener('submit', (e) => {
            e.preventDefault();
            const user = document.getElementById('loginUsername').value;
            const pass = document.getElementById('loginPassword').value;

            if (user === 'admin' && pass === '123456') {
                sessionStorage.setItem('hans_auth', 'true');
                loginError.classList.add('hidden');
                showDashboard();
            } else {
                loginError.classList.remove('hidden');
            }
        });

        logoutBtn.addEventListener('click', () => {
            sessionStorage.removeItem('hans_auth');
            appContainer.classList.add('hidden');
            loginPage.classList.remove('hidden');
        });

        function showDashboard() {
            loginPage.classList.add('hidden');
            appContainer.classList.remove('hidden');
            renderTable();
            updateStats();
        }

        function loadDatabase() {
            const saved = localStorage.getItem('hans_orders');
            if (saved) {
                try {
                    orders = JSON.parse(saved);
                } catch(e) {
                    orders = INITIAL_ORDERS;
                }
            } else {
                orders = INITIAL_ORDERS;
                saveDatabase();
            }
        }

        function saveDatabase() {
            localStorage.setItem('hans_orders', JSON.stringify(orders));
        }

        function setupCalculators() {
            const calcInputs = document.querySelectorAll('.calc-trigger');
            calcInputs.forEach(input => {
                input.addEventListener('input', calculateTotals);
            });
        }

        function calculateTotals() {
            const qtyShort = parseInt(document.getElementById('qtyShort').value) || 0;
            const priceShort = parseInt(document.getElementById('priceShort').value) || 0;
            const qtyLong = parseInt(document.getElementById('qtyLong').value) || 0;
            const priceLong = parseInt(document.getElementById('priceLong').value) || 0;
            const sizeCharge = parseInt(document.getElementById('priceSizeCharge').value) || 0;
            const dpAmount = parseInt(document.getElementById('inputDP').value) || 0;

            const totalQty = qtyShort + qtyLong;
            const totalPrice = (qtyShort * priceShort) + (qtyLong * priceLong) + sizeCharge;
            const remaining = totalPrice - dpAmount;

            document.getElementById('calculatedQtyDisplay').innerText = totalQty;
            document.getElementById('calculatedTotalDisplay').innerText = formatRupiah(totalPrice);
            document.getElementById('displayRemaining').value = formatRupiah(remaining > 0 ? remaining : 0);

            return { totalQty, totalPrice, dpAmount, remaining };
        }

        function formatRupiah(num) {
            return new Intl.NumberFormat('id-ID', { style: 'currency', currency: 'IDR', maximumFractionDigits: 0 }).format(num);
        }

        inputImageFile.addEventListener('change', function(e) {
            const file = e.target.files[0];
            if (file) {
                const reader = new FileReader();
                reader.onload = function(evt) {
                    currentBase64Image = evt.target.result;
                    imagePreview.src = currentBase64Image;
                    imagePreview.classList.remove('hidden');
                    noImgText.classList.add('hidden');
                };
                reader.readAsDataURL(file);
            }
        });

        // Render Tabel Order Utama
        function renderTable() {
            const query = searchInput.value.toLowerCase().trim();
            const statusVal = statusFilter.value;

            const filtered = orders.filter(ord => {
                const matchSearch = ord.customerName.toLowerCase().includes(query) || ord.id.toLowerCase().includes(query);
                const matchStatus = (statusVal === 'ALL') || (ord.status === statusVal);
                return matchSearch && matchStatus;
            });

            ordersTableBody.innerHTML = '';
            document.getElementById('orderCounter').innerText = `${filtered.length} Order`;

            filtered.forEach(item => {
                const sisa = item.totalPrice - (item.dpAmount || 0);
                const isLunas = sisa <= 0;

                const tr = document.createElement('tr');
                tr.className = "hover:bg-darkinput/40 transition border-b border-gray-800/60";

                tr.innerHTML = `
                    <td class="p-3">
                        <div class="flex items-center space-x-3">
                            <img src="${item.image || 'https://placehold.co/100x100/2a2a2a/888?text=No+Img'}" class="w-10 h-10 rounded-lg object-cover border border-gray-700 shrink-0">
                            <div>
                                <span class="font-bold text-white text-xs block">${item.id}</span>
                                <span class="text-[10px] text-gray-400">${item.totalQty} Pcs</span>
                            </div>
                        </div>
                    </td>
                    <td class="p-3 font-semibold text-gray-200">${item.customerName}</td>
                    <td class="p-3 text-xs">
                        <div><i class="far fa-calendar-alt text-gray-500 mr-1"></i> ${item.dateIn}</div>
                        <div class="text-red-400 font-medium"><i class="far fa-clock mr-1"></i> ${item.deadline}</div>
                    </td>
                    <td class="p-3 text-xs">
                        <span class="font-bold text-white block">${formatRupiah(item.totalPrice)}</span>
                        <span class="text-[10px] text-green-400">DP: ${formatRupiah(item.dpAmount || 0)}</span>
                    </td>
                    <td class="p-3 text-center">
                        ${isLunas ? 
                            `<span class="bg-green-950/80 text-green-400 border border-green-700/50 text-[11px] px-2.5 py-1 rounded-full font-medium">Lunas</span>` : 
                            `<span class="bg-yellow-950/80 text-yellow-400 border border-yellow-700/50 text-[10px] px-2 py-0.5 rounded-full block">Sisa: ${formatRupiah(sisa)}</span>`
                        }
                    </td>
                    <td class="p-3 text-center">
                        <select onchange="quickUpdateStatus('${item.id}', this.value)" class="bg-darkbg border border-gray-700 text-xs rounded px-2 py-1 text-gray-300 focus:outline-none focus:border-red-500">
                            <option value="Pending" ${item.status === 'Pending' ? 'selected' : ''}>Pending</option>
                            <option value="Proses" ${item.status === 'Proses' ? 'selected' : ''}>Proses</option>
                            <option value="Selesai" ${item.status === 'Selesai' ? 'selected' : ''}>Selesai</option>
                        </select>
                    </td>
                    <td class="p-3 text-center">
                        <div class="flex items-center justify-center space-x-2">
                            <button onclick="viewDetail('${item.id}')" title="Detail & SPK" class="p-1.5 bg-blue-950/60 text-blue-400 hover:text-white rounded border border-blue-800/40">
                                <i class="fas fa-eye text-xs"></i>
                            </button>
                            <button onclick="editOrder('${item.id}')" title="Edit" class="p-1.5 bg-yellow-950/60 text-yellow-400 hover:text-white rounded border border-yellow-800/40">
                                <i class="fas fa-edit text-xs"></i>
                            </button>
                            <button onclick="deleteOrder('${item.id}')" title="Hapus" class="p-1.5 bg-red-950/60 text-red-400 hover:text-white rounded border border-red-800/40">
                                <i class="fas fa-trash text-xs"></i>
                            </button>
                        </div>
                    </td>
                `;
                ordersTableBody.appendChild(tr);
            });
        }

        // Render Halaman Keuangan Harian
        function renderFinanceTable() {
            const selectedDate = financeDateFilter.value;
            financeTableBody.innerHTML = '';

            let totalReceived = 0;
            let totalDP = 0;
            let totalUnpaid = 0;
            let totalTarget = 0;

            const dayOrders = orders.filter(o => o.dateIn === selectedDate);

            dayOrders.forEach(item => {
                const sisa = item.totalPrice - (item.dpAmount || 0);
                totalReceived += (item.dpAmount || 0);
                totalDP += (item.dpAmount || 0);
                totalUnpaid += sisa > 0 ? sisa : 0;
                totalTarget += item.totalPrice;

                const tr = document.createElement('tr');
                tr.className = "hover:bg-darkinput/40 transition border-b border-gray-800/60";
                tr.innerHTML = `
                    <td class="p-3 font-bold text-xs text-white">${item.id}</td>
                    <td class="p-3">${item.customerName}</td>
                    <td class="p-3 font-semibold text-white">${formatRupiah(item.totalPrice)}</td>
                    <td class="p-3 text-green-400 font-bold">${formatRupiah(item.dpAmount || 0)}</td>
                    <td class="p-3 text-red-400">${formatRupiah(sisa > 0 ? sisa : 0)}</td>
                    <td class="p-3 text-center">
                        ${sisa <= 0 ? 
                            `<span class="bg-green-950/80 text-green-400 border border-green-700/50 text-[10px] px-2 py-0.5 rounded-full">LUNAS</span>` : 
                            `<span class="bg-yellow-950/80 text-yellow-400 border border-yellow-700/50 text-[10px] px-2 py-0.5 rounded-full">BELUM LUNAS</span>`
                        }
                    </td>
                `;
                financeTableBody.appendChild(tr);
            });

            document.getElementById('finTotalReceived').innerText = formatRupiah(totalReceived);
            document.getElementById('finTotalDP').innerText = formatRupiah(totalDP);
            document.getElementById('finTotalUnpaid').innerText = formatRupiah(totalUnpaid);
            document.getElementById('finTotalTarget').innerText = formatRupiah(totalTarget);
        }

        financeDateFilter.addEventListener('change', renderFinanceTable);

        function updateStats() {
            document.getElementById('statTotalOrders').innerText = orders.length;
            document.getElementById('statProcessingOrders').innerText = orders.filter(o => o.status === 'Proses').length;
            document.getElementById('statCompletedOrders').innerText = orders.filter(o => o.status === 'Selesai').length;

            const totalRev = orders.reduce((sum, o) => sum + (o.totalPrice || 0), 0);
            document.getElementById('statTotalRevenue').innerText = formatRupiah(totalRev);
        }

        searchInput.addEventListener('input', renderTable);
        statusFilter.addEventListener('change', renderTable);

        openNewOrderModal.addEventListener('click', () => {
            document.getElementById('modalTitle').innerText = "Tambah Pesanan Baru";
            document.getElementById('editOrderId').value = "";
            orderForm.reset();
            currentBase64Image = "";
            imagePreview.classList.add('hidden');
            noImgText.classList.remove('hidden');
            document.getElementById('inputDateIn').valueAsDate = new Date();
            calculateTotals();
            orderModal.classList.remove('hidden');
        });

        function closeModal() {
            orderModal.classList.add('hidden');
        }

        closeOrderModal.addEventListener('click', closeModal);
        cancelOrderModal.addEventListener('click', closeModal);

        orderForm.addEventListener('submit', (e) => {
            e.preventDefault();

            const editId = document.getElementById('editOrderId').value;
            const totals = calculateTotals();

            const newOrderData = {
                id: editId || ("ORD-" + Math.floor(1000 + Math.random() * 9000)),
                customerName: document.getElementById('inputCustomerName').value,
                dateIn: document.getElementById('inputDateIn').value,
                deadline: document.getElementById('inputDeadline').value,
                status: document.getElementById('inputStatus').value,
                
                qtyShort: parseInt(document.getElementById('qtyShort').value) || 0,
                priceShort: parseInt(document.getElementById('priceShort').value) || 0,
                qtyLong: parseInt(document.getElementById('qtyLong').value) || 0,
                priceLong: parseInt(document.getElementById('priceLong').value) || 0,
                
                sizeExtraNote: document.getElementById('sizeExtraNote').value,
                priceSizeCharge: parseInt(document.getElementById('priceSizeCharge').value) || 0,
                
                totalQty: totals.totalQty,
                totalPrice: totals.totalPrice,
                dpAmount: totals.dpAmount,
                image: currentBase64Image || (editId ? (orders.find(o => o.id === editId)?.image || "") : "https://placehold.co/400x400/2a2a2a/dc2626?text=Jersey")
            };

            if (editId) {
                const index = orders.findIndex(o => o.id === editId);
                if (index !== -1) orders[index] = newOrderData;
            } else {
                orders.unshift(newOrderData);
            }

            saveDatabase();
            renderTable();
            updateStats();
            closeModal();
        });

        window.quickUpdateStatus = function(id, newStatus) {
            const item = orders.find(o => o.id === id);
            if (item) {
                item.status = newStatus;
                saveDatabase();
                updateStats();
            }
        };

        window.editOrder = function(id) {
            const item = orders.find(o => o.id === id);
            if (!item) return;

            document.getElementById('modalTitle').innerText = "Edit Pesanan - " + item.id;
            document.getElementById('editOrderId').value = item.id;
            document.getElementById('inputCustomerName').value = item.customerName;
            document.getElementById('inputDateIn').value = item.dateIn;
            document.getElementById('inputDeadline').value = item.deadline;
            document.getElementById('inputStatus').value = item.status;

            document.getElementById('qtyShort').value = item.qtyShort;
            document.getElementById('priceShort').value = item.priceShort;
            document.getElementById('qtyLong').value = item.qtyLong;
            document.getElementById('priceLong').value = item.priceLong;

            document.getElementById('sizeExtraNote').value = item.sizeExtraNote || "";
            document.getElementById('priceSizeCharge').value = item.priceSizeCharge || 0;
            document.getElementById('inputDP').value = item.dpAmount || 0;

            currentBase64Image = item.image || "";
            if (currentBase64Image) {
                imagePreview.src = currentBase64Image;
                imagePreview.classList.remove('hidden');
                noImgText.classList.add('hidden');
            } else {
                imagePreview.classList.add('hidden');
                noImgText.classList.remove('hidden');
            }

            calculateTotals();
            orderModal.classList.remove('hidden');
        };

        window.deleteOrder = function(id) {
            if (confirm(`Apakah Anda yakin ingin menghapus order ${id}?`)) {
                orders = orders.filter(o => o.id !== id);
                saveDatabase();
                renderTable();
                updateStats();
            }
        };

        window.viewDetail = function(id) {
            const item = orders.find(o => o.id === id);
            if (!item) return;

            const sisa = item.totalPrice - (item.dpAmount || 0);

            detailContent.innerHTML = `
                <div class="text-center border-b border-gray-800 pb-3">
                    <h2 class="text-xl font-black fire-gradient-text">HANS SUBLIM & PRINTING</h2>
                    <p class="text-xs text-gray-400">Nota Pesanan / Surat Perintah Kerja</p>
                    <p class="text-xs font-bold text-red-500 mt-1">${item.id}</p>
                </div>

                <div class="space-y-2 text-xs">
                    <div class="flex justify-between"><span class="text-gray-400">Customer:</span> <span class="font-bold text-white">${item.customerName}</span></div>
                    <div class="flex justify-between"><span class="text-gray-400">Tgl Masuk:</span> <span class="text-gray-200">${item.dateIn}</span></div>
                    <div class="flex justify-between"><span class="text-gray-400">Deadline:</span> <span class="text-red-400 font-bold">${item.deadline}</span></div>
                </div>

                <div class="border-t border-gray-800 pt-3">
                    <table class="w-full text-xs text-left">
                        <tr class="text-gray-500 border-b border-gray-800">
                            <th class="py-1">Jenis</th>
                            <th class="py-1 text-center">Qty</th>
                            <th class="py-1 text-right">Subtotal</th>
                        </tr>
                        <tr>
                            <td class="py-1">Lengan Pendek</td>
                            <td class="text-center">${item.qtyShort}</td>
                            <td class="text-right">${formatRupiah(item.qtyShort * item.priceShort)}</td>
                        </tr>
                        <tr>
                            <td class="py-1">Lengan Panjang</td>
                            <td class="text-center">${item.qtyLong}</td>
                            <td class="text-right">${formatRupiah(item.qtyLong * item.priceLong)}</td>
                        </tr>
                        ${item.priceSizeCharge > 0 ? `
                        <tr>
                            <td class="py-1">Cas Jumbo (${item.sizeExtraNote})</td>
                            <td class="text-center">-</td>
                            <td class="text-right">${formatRupiah(item.priceSizeCharge)}</td>
                        </tr>` : ''}
                    </table>
                </div>

                <div class="bg-darkbg p-3 rounded-lg space-y-1 font-semibold text-xs border border-gray-800">
                    <div class="flex justify-between"><span>Total Tagihan:</span> <span class="text-white">${formatRupiah(item.totalPrice)}</span></div>
                    <div class="flex justify-between text-green-400"><span>Uang Muka (DP):</span> <span>- ${formatRupiah(item.dpAmount || 0)}</span></div>
                    <div class="flex justify-between text-sm font-bold border-t border-gray-800 pt-1 text-yellow-400">
                        <span>Sisa Pembayaran:</span> <span>${formatRupiah(sisa > 0 ? sisa : 0)}</span>
                    </div>
                </div>

                <div class="border-t border-gray-800 pt-3 text-center">
                    <img src="${item.image}" class="max-h-40 mx-auto rounded-lg border border-gray-700 object-contain">
                </div>
            `;

            detailModal.classList.remove('hidden');
        };

        closeDetailModal.addEventListener('click', () => detailModal.classList.add('hidden'));
        closeDetailBtn.addEventListener('click', () => detailModal.classList.add('hidden'));
        printOrderBtn.addEventListener('click', () => window.print());
    </script>
</body>
</html>
