<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hans Order Management System</title>
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
    </style>
</head>
<body class="bg-darkbg text-gray-200 min-h-screen font-sans flex flex-col antialiased">

    
    <!-- LOGIN SCREEN -->
    <div id="loginPage" class="fixed inset-0 z-50 flex items-center justify-center bg-darkbg px-4">
        <div class="bg-darkcard border border-gray-800 rounded-2xl p-8 max-w-md w-full shadow-2xl fire-border-glow text-center">
            <!-- Logo Hans Display -->
            <div class="relative w-28 h-28 mx-auto mb-4 rounded-full p-1 bg-gradient-to-tr from-red-600 via-orange-500 to-yellow-400 shadow-lg flex items-center justify-center">
                <div class="w-full h-full bg-darkbg rounded-full flex flex-col items-center justify-center p-2 border border-black/50">
                    <span class="text-3xl font-black tracking-wider text-red-500 italic">Hans</span>
                    <span class="text-[9px] uppercase tracking-widest text-gray-400 -mt-1 font-semibold">Sublim & Printing</span>
                </div>
            </div>

            <h2 class="text-2xl font-bold fire-gradient-text mb-1">Hans Production</h2>
            <p class="text-xs text-gray-400 mb-6">Sistem Manajemen Order & Produksi</p>

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
                <div class="flex items-center space-x-3">
                    <div class="w-10 h-10 rounded-full bg-gradient-to-tr from-red-600 to-yellow-500 p-0.5 flex items-center justify-center">
                        <div class="w-full h-full bg-darkbg rounded-full flex flex-col items-center justify-center p-1">
                            <span class="text-xs font-black text-red-500 italic">Hans</span>
                        </div>
                    </div>
                    <div>
                        <h1 class="text-lg font-bold tracking-wide text-white flex items-center">
                            Hans <span class="ml-1 text-xs text-red-500 font-semibold px-2 py-0.5 rounded bg-red-950/60 border border-red-800/40">Management</span>
                        </h1>
                        <p class="text-[10px] text-gray-400">Database & Order Tracking System</p>
                    </div>
                </div>

                <div class="flex items-center space-x-4">
                    <div class="hidden md:flex items-center space-x-2 text-xs text-gray-400 bg-darkbg px-3 py-1.5 rounded-lg border border-gray-800">
                        <i class="fas fa-user-circle text-red-500 text-sm"></i>
                        <span>Admin Production</span>
                    </div>
                    <button id="logoutBtn" class="bg-gray-800 hover:bg-red-900/60 text-gray-300 hover:text-red-300 text-xs px-3 py-2 rounded-lg border border-gray-700 transition flex items-center space-x-1">
                        <i class="fas fa-power-off"></i>
                        <span class="hidden sm:inline">Keluar</span>
                    </button>
                </div>
            </div>
        </header>

        <!-- MAIN CONTENT AREA -->
        <main class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-6 flex-1 w-full space-y-6">
            
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
                        <i class="fas fa-spinner text-xl animate-spin-slow"></i>
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
                        <p class="text-xs text-gray-400">Omset Total</p>
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
                                <th class="p-3">Tanggal / Deadline</th>
                                <th class="p-3">Rincian Qty</th>
                                <th class="p-3">Total Tagihan</th>
                                <th class="p-3 text-center">Status</th>
                                <th class="p-3 text-center">Aksi</th>
                            </tr>
                        </thead>
                        <tbody id="ordersTableBody" class="divide-y divide-gray-800 text-gray-300">
                            <!-- JS Inject Table Rows Here -->
                        </tbody>
                    </table>
                </div>

                <div id="emptyState" class="hidden p-12 text-center">
                    <i class="fas fa-folder-open text-4xl text-gray-600 mb-3"></i>
                    <p class="text-gray-400 text-sm">Belum ada data order yang cocok.</p>
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
                            <label class="block text-xs text-gray-400 mb-1">Status Awal</label>
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
                        <!-- Lengan Pendek -->
                        <div class="bg-darkbg p-3 rounded-xl border border-gray-800 space-y-2">
                            <span class="text-xs font-semibold text-gray-300 block border-b border-gray-800 pb-1">
                                <i class="fas fa-[#tshirt] text-orange-400 mr-1"></i> Lengan Pendek
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

                        <!-- Lengan Panjang -->
                        <div class="bg-darkbg p-3 rounded-xl border border-gray-800 space-y-2">
                            <span class="text-xs font-semibold text-gray-300 block border-b border-gray-800 pb-1">
                                <i class="fas fa-tshirt text-yellow-400 mr-1"></i> Lengan Panjang
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

                        <!-- Cas Ukuran Jumbo -->
                        <div class="md:col-span-2 bg-darkbg p-3 rounded-xl border border-gray-800 space-y-2">
                            <span class="text-xs font-semibold text-gray-300 block border-b border-gray-800 pb-1">
                                <i class="fas fa-expand-alt text-red-400 mr-1"></i> Surcharge / Cas Ukuran Jumbo (XXL, 3XL, dst)
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

                <!-- TOTAL RINGKASAN HARGA -->
                <div class="bg-gradient-to-r from-red-950/40 via-darkbg to-darkbg border border-red-900/50 p-4 rounded-xl flex items-center justify-between">
                    <div>
                        <span class="text-xs text-gray-400 block">Total Estimasi Tagihan:</span>
                        <span id="calculatedTotalDisplay" class="text-xl font-bold text-yellow-400">Rp 0</span>
                    </div>
                    <div class="text-right text-xs text-gray-400">
                        Total Pcs: <span id="calculatedQtyDisplay" class="text-white font-bold">0</span> Pcs
                    </div>
                </div>

                <!-- UPLOAD GAMBAR DESAIN PRODUKSI -->
                <div>
                    <h4 class="text-xs uppercase font-bold text-red-400 tracking-wider mb-3">3. Foto Desain Order Produksi</h4>
                    <div class="flex flex-col sm:flex-row items-center gap-4">
                        <div id="imagePreviewContainer" class="w-32 h-32 bg-darkbg border-2 border-dashed border-gray-700 rounded-xl flex items-center justify-center overflow-hidden shrink-0 relative">
                            <span id="noImgText" class="text-xs text-gray-500 text-center p-2">Belum ada gambar</span>
                            <img id="imagePreview" class="hidden w-full h-full object-cover">
                        </div>
                        <div class="flex-1 w-full space-y-2">
                            <label class="block text-xs text-gray-400">Upload Desain / Template Jersey</label>
                            <input type="file" id="inputImageFile" accept="image/*" class="block w-full text-xs text-gray-400 file:mr-4 file:py-2 file:px-4 file:rounded-lg file:border-0 file:text-xs file:font-semibold file:bg-red-950/60 file:text-red-300 hover:file:bg-red-900 cursor-pointer border border-gray-800 rounded-lg bg-darkbg">
                            <p class="text-[10px] text-gray-500">Format JPG, PNG. Gambar disimpan otomatis secara lokal.</p>
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

    <!-- DETAIL / VIEW ORDER MODAL -->
    <div id="detailModal" class="fixed inset-0 z-50 bg-black/80 backdrop-blur-sm hidden flex items-center justify-center p-4">
        <div class="bg-darkcard border border-gray-800 rounded-2xl w-full max-w-lg overflow-hidden shadow-2xl flex flex-col">
            <div class="p-4 bg-darkbg border-b border-gray-800 flex justify-between items-center">
                <h3 class="text-lg font-bold text-white flex items-center space-x-2">
                    <i class="fas fa-info-circle text-red-500"></i>
                    <span>Rincian Order Hans Printing</span>
                </h3>
                <button id="closeDetailModal" class="text-gray-400 hover:text-white">
                    <i class="fas fa-times text-lg"></i>
                </button>
            </div>

            <div id="detailContent" class="p-6 space-y-4 overflow-y-auto max-h-[80vh]">
                <!-- JS Populated -->
            </div>

            <div class="p-4 bg-darkbg border-t border-gray-800 flex justify-between items-center">
                <button id="printOrderBtn" class="bg-gray-800 hover:bg-gray-700 text-gray-300 text-xs px-3 py-2 rounded-lg border border-gray-700 flex items-center space-x-1">
                    <i class="fas fa-print"></i>
                    <span>Cetak Nota / SPK</span>
                </button>
                <button id="closeDetailBtn" class="bg-red-600 hover:bg-red-500 text-white text-xs px-4 py-2 rounded-lg font-semibold">Tutup</button>
            </div>
        </div>
    </div>

    <script>
        // Default Sample Data if LocalStorage empty
        const INITIAL_ORDERS = [
            {
                id: "ORD-1001",
                customerName: "Tim Futsal FC Renegade",
                dateIn: "2026-03-20",
                deadline: "2026-03-28",
                qtyShort: 12,
                priceShort: 75000,
                qtyLong: 3,
                priceLong: 85000,
                sizeExtraNote: "XXL 2Pcs",
                priceSizeCharge: 20000,
                totalPrice: 1175000,
                totalQty: 15,
                status: "Proses",
                image: "https://placehold.co/400x400/2a2a2a/dc2626?text=Jersey+Renegade"
            },
            {
                id: "ORD-1002",
                customerName: "Komunitas Motor Vixion",
                dateIn: "2026-03-22",
                deadline: "2026-04-02",
                qtyShort: 25,
                priceShort: 70000,
                qtyLong: 5,
                priceLong: 80000,
                sizeExtraNote: "3XL 1Pc",
                priceSizeCharge: 15000,
                totalPrice: 2165000,
                totalQty: 30,
                status: "Pending",
                image: "https://placehold.co/400x400/2a2a2a/eab308?text=Kaos+Vixion"
            }
        ];

        // State Store
        let orders = [];
        let currentBase64Image = "";

        // DOM Element Selectors
        const loginPage = document.getElementById('loginPage');
        const loginForm = document.getElementById('loginForm');
        const loginError = document.getElementById('loginError');
        const appContainer = document.getElementById('appContainer');
        const logoutBtn = document.getElementById('logoutBtn');

        const ordersTableBody = document.getElementById('ordersTableBody');
        const emptyState = document.getElementById('emptyState');
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

        
        // Initialize App
        window.addEventListener('DOMContentLoaded', () => {
            loadDatabase();
            setupCalculators();
            
            // Check session login state
            if (sessionStorage.getItem('hans_auth') === 'true') {
                showDashboard();
            }
        });

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

        // Database LocalStorage Functions
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

            const totalQty = qtyShort + qtyLong;
            const totalPrice = (qtyShort * priceShort) + (qtyLong * priceLong) + sizeCharge;

            document.getElementById('calculatedQtyDisplay').innerText = totalQty;
            document.getElementById('calculatedTotalDisplay').innerText = formatRupiah(totalPrice);

            return { totalQty, totalPrice };
        }

        function formatRupiah(num) {
            return new Intl.NumberFormat('id-ID', { style: 'currency', currency: 'IDR', maximumFractionDigits: 0 }).format(num);
        }

        // Image Reader File Converter
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

        // Render Table Data
        function renderTable() {
            const query = searchInput.value.toLowerCase();
            const filterVal = statusFilter.value;

            ordersTableBody.innerHTML = '';

            const filteredOrders = orders.filter(ord => {
                const matchesSearch = ord.customerName.toLowerCase().includes(query) || ord.id.toLowerCase().includes(query);
                const matchesStatus = filterVal === 'ALL' || ord.status === filterVal;
                return matchesSearch && matchesStatus;
            });

            document.getElementById('orderCounter').innerText = `${filteredOrders.length} Order`;

            if (filteredOrders.length === 0) {
                emptyState.classList.remove('hidden');
                return;
            } else {
                emptyState.classList.add('hidden');
            }

            filteredOrders.forEach(ord => {
                const tr = document.createElement('tr');
                tr.className = "hover:bg-gray-800/50 transition";

                let statusBadge = '';
                if(ord.status === 'Pending') {
                    statusBadge = `<span class="px-2.5 py-1 rounded-full text-[11px] font-semibold bg-gray-800 text-yellow-400 border border-yellow-800/40"><i class="fas fa-clock mr-1"></i>Pending</span>`;
                } else if(ord.status === 'Proses') {
                    statusBadge = `<span class="px-2.5 py-1 rounded-full text-[11px] font-semibold bg-blue-950/70 text-blue-400 border border-blue-800/40"><i class="fas fa-cog fa-spin mr-1"></i>Proses</span>`;
                } else {
                    statusBadge = `<span class="px-2.5 py-1 rounded-full text-[11px] font-semibold bg-green-950/70 text-green-400 border border-green-800/40"><i class="fas fa-check mr-1"></i>Selesai</span>`;
                }

                const thumb = ord.image || 'https://placehold.co/100x100/2a2a2a/666?text=No+Img';

                tr.innerHTML = `
                    <td class="p-3">
                        <div class="flex items-center space-x-3">
                            <img src="${thumb}" class="w-12 h-12 object-cover rounded-lg bg-darkinput border border-gray-700 shrink-0">
                            <div>
                                <span class="font-bold text-white text-xs block">${ord.id}</span>
                                <span class="text-[11px] text-gray-500">${ord.totalQty} Pcs Total</span>
                            </div>
                        </div>
                    </td>
                    <td class="p-3 font-medium text-white">${escapeHtml(ord.customerName)}</td>
                    <td class="p-3">
                        <div class="text-xs">
                            <div class="text-gray-400"><i class="far fa-calendar-alt mr-1"></i>Masuk: ${ord.dateIn}</div>
                            <div class="text-red-400 font-semibold"><i class="far fa-calendar-check mr-1"></i>Deadline: ${ord.deadline}</div>
                        </div>
                    </td>
                    <td class="p-3 text-xs text-gray-300">
                        <div>Lgn Pendek: <b>${ord.qtyShort}</b> Pcs</div>
                        <div>Lgn Panjang: <b>${ord.qtyLong}</b> Pcs</div>
                    </td>
                    <td class="p-3 font-bold text-yellow-400">${formatRupiah(ord.totalPrice)}</td>
                    <td class="p-3 text-center">${statusBadge}</td>
                    <td class="p-3 text-center">
                        <div class="flex items-center justify-center space-x-2">
                            <button onclick="viewDetail('${ord.id}')" title="Lihat Detail" class="p-2 bg-gray-800 hover:bg-gray-700 text-blue-400 rounded-lg transition">
                                <i class="fas fa-eye"></i>
                            </button>
                            <button onclick="editOrder('${ord.id}')" title="Edit Order" class="p-2 bg-gray-800 hover:bg-gray-700 text-yellow-400 rounded-lg transition">
                                <i class="fas fa-edit"></i>
                            </button>
                            <button onclick="deleteOrder('${ord.id}')" title="Hapus Order" class="p-2 bg-gray-800 hover:bg-red-900/60 text-red-400 rounded-lg transition">
                                <i class="fas fa-trash-alt"></i>
                            </button>
                        </div>
                    </td>
                `;
                ordersTableBody.appendChild(tr);
            });
        }

        function updateStats() {
            const totalOrders = orders.length;
            const processing = orders.filter(o => o.status === 'Proses').length;
            const completed = orders.filter(o => o.status === 'Selesai').length;
            const revenue = orders.reduce((sum, o) => sum + o.totalPrice, 0);

            document.getElementById('statTotalOrders').innerText = totalOrders;
            document.getElementById('statProcessingOrders').innerText = processing;
            document.getElementById('statCompletedOrders').innerText = completed;
            document.getElementById('statTotalRevenue').innerText = formatRupiah(revenue);
        }

        // Modal Operations (Add / Edit)
        openNewOrderModal.addEventListener('click', () => {
            resetModalForm();
            document.getElementById('modalTitle').innerHTML = `<i class="fas fa-plus-circle text-red-500"></i><span>Tambah Pesanan Baru</span>`;
            
            // Set default date
            const today = new Date().toISOString().split('T')[0];
            document.getElementById('inputDateIn').value = today;
            
            orderModal.classList.remove('hidden');
        });

        function closeModal() {
            orderModal.classList.add('hidden');
        }

        closeOrderModal.addEventListener('click', closeModal);
        cancelOrderModal.addEventListener('click', closeModal);

        function resetModalForm() {
            orderForm.reset();
            document.getElementById('editOrderId').value = '';
            currentBase64Image = '';
            imagePreview.src = '';
            imagePreview.classList.add('hidden');
            noImgText.classList.remove('hidden');
            calculateTotals();
        }

        // Handle Save Order
        orderForm.addEventListener('submit', (e) => {
            e.preventDefault();

            const editId = document.getElementById('editOrderId').value;
            const calc = calculateTotals();

            const orderData = {
                id: editId ? editId : 'ORD-' + Math.floor(1000 + Math.random() * 9000),
                customerName: document.getElementById('inputCustomerName').value,
                dateIn: document.getElementById('inputDateIn').value,
                deadline: document.getElementById('inputDeadline').value,
                qtyShort: parseInt(document.getElementById('qtyShort').value) || 0,
                priceShort: parseInt(document.getElementById('priceShort').value) || 0,
                qtyLong: parseInt(document.getElementById('qtyLong').value) || 0,
                priceLong: parseInt(document.getElementById('priceLong').value) || 0,
                sizeExtraNote: document.getElementById('sizeExtraNote').value,
                priceSizeCharge: parseInt(document.getElementById('priceSizeCharge').value) || 0,
                totalPrice: calc.totalPrice,
                totalQty: calc.totalQty,
                status: document.getElementById('inputStatus').value,
                image: currentBase64Image || 'https://placehold.co/400x400/2a2a2a/dc2626?text=Order+Hans'
            };

            if (editId) {
                // Update Existing
                const idx = orders.findIndex(o => o.id === editId);
                if (idx !== -1) {
                    orders[idx] = orderData;
                }
            } else {
                // Insert New
                orders.unshift(orderData);
            }

            saveDatabase();
            renderTable();
            updateStats();
            closeModal();
        });

        // Edit Existing Order
        window.editOrder = function(id) {
            const ord = orders.find(o => o.id === id);
            if (!ord) return;

            resetModalForm();
            document.getElementById('modalTitle').innerHTML = `<i class="fas fa-edit text-yellow-500"></i><span>Edit Pesanan ${ord.id}</span>`;
            document.getElementById('editOrderId').value = ord.id;
            
            document.getElementById('inputCustomerName').value = ord.customerName;
            document.getElementById('inputDateIn').value = ord.dateIn;
            document.getElementById('inputDeadline').value = ord.deadline;
            document.getElementById('inputStatus').value = ord.status;

            document.getElementById('qtyShort').value = ord.qtyShort;
            document.getElementById('priceShort').value = ord.priceShort;
            document.getElementById('qtyLong').value = ord.qtyLong;
            document.getElementById('priceLong').value = ord.priceLong;
            document.getElementById('sizeExtraNote').value = ord.sizeExtraNote || '';
            document.getElementById('priceSizeCharge').value = ord.priceSizeCharge || 0;

            if (ord.image) {
                currentBase64Image = ord.image;
                imagePreview.src = ord.image;
                imagePreview.classList.remove('hidden');
                noImgText.classList.add('hidden');
            }

            calculateTotals();
            orderModal.classList.remove('hidden');
        };

        // Delete Order
        window.deleteOrder = function(id) {
            if (confirm(`Apakah Anda yakin ingin menghapus pesanan ${id}?`)) {
                orders = orders.filter(o => o.id !== id);
                saveDatabase();
                renderTable();
                updateStats();
            }
        };

        let activeDetailOrder = null;

        window.viewDetail = function(id) {
            const ord = orders.find(o => o.id === id);
            if (!ord) return;

            activeDetailOrder = ord;

            let statusBadge = '';
            if(ord.status === 'Pending') statusBadge = '<span class="text-yellow-400 font-bold">Pending</span>';
            else if(ord.status === 'Proses') statusBadge = '<span class="text-blue-400 font-bold">Dalam Proses</span>';
            else statusBadge = '<span class="text-green-400 font-bold">Selesai</span>';

            detailContent.innerHTML = `
                <div class="text-center pb-4 border-b border-gray-800">
                    <span class="text-xs text-gray-500 uppercase tracking-widest">ID Order</span>
                    <h2 class="text-2xl font-black text-white">${ord.id}</h2>
                    <p class="text-xs text-gray-400">Status: ${statusBadge}</p>
                </div>

                <div class="space-y-3">
                    <div>
                        <span class="text-xs text-gray-500">Nama Customer:</span>
                        <p class="font-bold text-white text-base">${escapeHtml(ord.customerName)}</p>
                    </div>

                    <div class="grid grid-cols-2 gap-2 text-xs bg-darkbg p-3 rounded-lg border border-gray-800">
                        <div>
                            <span class="text-gray-500">Tanggal Masuk:</span>
                            <p class="text-gray-200 font-medium">${ord.dateIn}</p>
                        </div>
                        <div>
                            <span class="text-gray-500">Deadline:</span>
                            <p class="text-red-400 font-bold">${ord.deadline}</p>
                        </div>
                    </div>

                    <div class="border-t border-b border-gray-800 py-3 space-y-2">
                        <span class="text-xs font-bold text-red-400 uppercase">Rincian Produk</span>
                        <div class="flex justify-between text-xs">
                            <span class="text-gray-300">Lengan Pendek (${ord.qtyShort} Pcs x ${formatRupiah(ord.priceShort)})</span>
                            <span class="font-semibold text-white">${formatRupiah(ord.qtyShort * ord.priceShort)}</span>
                        </div>
                        <div class="flex justify-between text-xs">
                            <span class="text-gray-300">Lengan Panjang (${ord.qtyLong} Pcs x ${formatRupiah(ord.priceLong)})</span>
                            <span class="font-semibold text-white">${formatRupiah(ord.qtyLong * ord.priceLong)}</span>
                        </div>
                        ${ord.priceSizeCharge > 0 ? `
                        <div class="flex justify-between text-xs text-orange-400">
                            <span>Cas Size Jumbo (${escapeHtml(ord.sizeExtraNote || 'Extra')})</span>
                            <span class="font-semibold">${formatRupiah(ord.priceSizeCharge)}</span>
                        </div>` : ''}
                    </div>

                    <div class="flex justify-between items-center text-sm font-bold bg-gray-800 p-3 rounded-lg">
                        <span class="text-gray-300">Total Pembayaran:</span>
                        <span class="text-yellow-400 text-lg">${formatRupiah(ord.totalPrice)}</span>
                    </div>

                    <div>
                        <span class="text-xs text-gray-500 block mb-2">Gambar / Desain Produksi:</span>
                        <img src="${ord.image}" class="w-full max-h-60 object-contain bg-darkbg border border-gray-800 rounded-xl p-2">
                    </div>
                </div>
            `;

            detailModal.classList.remove('hidden');
        };

        closeDetailModal.addEventListener('click', () => detailModal.classList.add('hidden'));
        closeDetailBtn.addEventListener('click', () => detailModal.classList.add('hidden'));

        // Print Order / Invoice Handler
        printOrderBtn.addEventListener('click', () => {
            if (!activeDetailOrder) return;
            const printWin = window.open('', '_blank');
            printWin.document.write(`
                <html>
                <head>
                    <title>SPK / Invoice - ${activeDetailOrder.id}</title>
                    <style>
                        body { font-family: sans-serif; padding: 20px; color: #000; }
                        h1 { font-size: 20px; margin-bottom: 0; }
                        .table { width: 100%; border-collapse: collapse; margin-top: 15px; }
                        .table th, .table td { border: 1px solid #ccc; padding: 8px; text-align: left; font-size: 13px; }
                        .total { font-size: 16px; font-weight: bold; }
                        img { max-width: 300px; margin-top: 15px; border: 1px solid #ccc; }
                    </style>
                </head>
                <body>
                    <h1>HANS CUSTOM PRINTING & SUBLIMATION</h1>
                    <p>SPK / NOTA PESANAN PRODUKSI</p>
                    <hr>
                    <p><b>ID Order:</b> ${activeDetailOrder.id}</p>
                    <p><b>Customer:</b> ${activeDetailOrder.customerName}</p>
                    <p><b>Tanggal Masuk:</b> ${activeDetailOrder.dateIn} | <b>Deadline:</b> ${activeDetailOrder.deadline}</p>
                    
                    <table class="table">
                        <thead>
                            <tr>
                                <th>Item</th>
                                <th>Qty</th>
                                <th>Harga Unit</th>
                                <th>Subtotal</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td>Lengan Pendek</td>
                                <td>${activeDetailOrder.qtyShort} Pcs</td>
                                <td>${formatRupiah(activeDetailOrder.priceShort)}</td>
                                <td>${formatRupiah(activeDetailOrder.qtyShort * activeDetailOrder.priceShort)}</td>
                            </tr>
                            <tr>
                                <td>Lengan Panjang</td>
                                <td>${activeDetailOrder.qtyLong} Pcs</td>
                                <td>${formatRupiah(activeDetailOrder.priceLong)}</td>
                                <td>${formatRupiah(activeDetailOrder.qtyLong * activeDetailOrder.priceLong)}</td>
                            </tr>
                            ${activeDetailOrder.priceSizeCharge > 0 ? `
                            <tr>
                                <td>Cas Ukuran Jumbo (${activeDetailOrder.sizeExtraNote})</td>
                                <td>-</td>
                                <td>-</td>
                                <td>${formatRupiah(activeDetailOrder.priceSizeCharge)}</td>
                            </tr>
                            ` : ''}
                        </tbody>
                    </table>

                    <p class="total">TOTAL TAGIHAN: ${formatRupiah(activeDetailOrder.totalPrice)}</p>
                    <br>
                    <p><b>Lampiran Desain Produksi:</b></p>
                    <img src="${activeDetailOrder.image}">
                    <script>
                        window.onload = function() { window.print(); }
                    <\/script>
                </body>
                </html>
            `);
            printWin.document.close();
        });

        // Search and Filter Listeners
        searchInput.addEventListener('input', renderTable);
        statusFilter.addEventListener('change', renderTable);

        // Utility Helper
        function escapeHtml(str) {
            return String(str).replace(/&/g, '&amp;').replace(/</g, '&lt;').replace(/>/g, '&gt;').replace(/"/g, '&quot;');
        }
    </script>
</body>
</html>
