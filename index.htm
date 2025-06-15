import React, { useState, useEffect } from "react";
import { FiZap, FiUser, FiHome, FiMapPin, FiLock, FiGift } from "react-icons/fi";

function NarasiDinamis({ currentPage }) {
  let narasi = null;
  switch (currentPage) {
    case "Tentang":
      narasi = (
        <div className="text-left text-base md:text-lg text-gray-800 max-w-3xl mx-auto px-4 animate-fadeIn">
          <p className="mb-4">
            <strong className="text-purple-700">Mandiri Cell</strong> adalah mitra terpercaya dalam bisnis <span className="text-blue-700 font-semibold">pulsa</span> dan <span className="text-blue-700 font-semibold">PPOB</span> sejak tahun 2020. Kami menghadirkan layanan unggulan melalui aplikasi dan server yang stabil untuk menunjang kesuksesan Anda dalam dunia digital.
          </p>
          <p className="mb-4">
            Dengan pengalaman dan komitmen yang tinggi, <strong className="text-purple-700">Mandiri Cell</strong> terus berkembang untuk memberikan pelayanan terbaik bagi para mitra dan pelanggannya.
          </p>
        </div>
      );
      break;
    case "Server":
      narasi = (
        <div className="text-left text-base md:text-lg text-gray-800 max-w-3xl mx-auto px-4 animate-fadeIn">
          <p className="mb-4">
            <strong className="text-blue-700">Server Mandiri Cell</strong> adalah solusi terbaik untuk kamu yang ingin memulai bisnis digital dengan mudah, cepat, dan tanpa ribet. Sebagai server pulsa all operator, Mandiri Cell menyediakan layanan transaksi isi pulsa, paket data, token listrik, dan berbagai jenis pembayaran tagihan PPOB (listrik, PDAM, BPJS, internet, dan lainnya). 
          <p className="mt-4">Keunggulan kami terletak pada sistem transaksi otomatis <span className="text-green-500 font-bold">24 jam non-stop</span> yang bisa dilakukan melalui:
          <p className="mt-4">
            <strong>✅ WhatsApp</strong>
          </p>
            <p><strong>✅ Telegram</strong></p>
            <p><strong>✅ Aplikasi Galeri Pulsa</strong></p>
            <p>
             Dengan <span className="text-blue-700 font-bold">Server Mandiri Cell</span>, semua transaksi bisa dilakukan dari genggaman tanganmu — cukup dengan <span className="text-pink-600">smartphone</span> dan <span className="text-pink-600">koneksi internet</span>. Kamu tidak perlu lagi repot stok barang atau membuka toko fisik. Semua bisa dilakukan dari rumah!</p>
          </p>
            </p>
          <p className="mt-10 text-2xl font-bold">Kenapa Harus <span className="text-blue-700">Mandiri Cell</span>?</p>
          <p className="mt-2">
             <p>💰 Harga produk bersaing, cocok untuk semua kalangan</p>
             <p>📱 Transaksi mudah via aplikasi, WA, atau Telegram</p>
             <p>📈 Bisa mendaftarkan downline untuk tambahan penghasilan</p>
             <p>🕛 Layanan aktif 24 jam nonstop</p>
             <p>🎁 Banyak promo dan bonus</p>
             <p>🧾 Laporan transaksi lengkap dan transparan</p>
             <span className="text-purple-700">
             <p className="mt-4">Mulailah usaha mandiri kamu sekarang. Ribuan pengguna telah bergabung dan menikmati keuntungan setiap harinya.</p></span>
          </p>
          
          
        </div>
      );
      break;
    case "Aplikasi":
      narasi = (
        <div className="text-left text-base md:text-lg text-gray-800 max-w-3xl mx-auto px-4 animate-fadeIn">
          <p className="mb-4">
            <strong className="text-pink-600">Aplikasi Galeri Pulsa</strong> dari <strong className="text-purple-600">Mandiri Cell</strong> dirancang untuk memberikan <span className="font-semibold text-green-600">kemudahan</span> dan <span className="font-semibold text-green-600">kenyamanan</span> dalam bertransaksi pulsa dan PPOB langsung dari genggaman Anda.
          </p>
          <ul className="list-disc pl-7 text-gray-700">
            <li>Interface sederhana dan user-friendly</li>
            <li>Transaksi cepat dan real-time</li>
            <li>Fitur downline untuk pengembangan jaringan</li>
          </ul>
          <p className="mt-4">
            Cocok bagi pemula maupun profesional yang ingin mengelola bisnis digital secara fleksibel dan efisien.
          </p>
        </div>
      );
      break;
    case "Beranda":
      narasi = (
        <div className="text-center text-lg md:text-xl text-gray-800 animate-fadeIn">
          <p className="mb-2">
            <span className="text-2xl font-bold text-yellow-600">Selamat datang di Mandiri Cell!</span>
          </p>
          <p>
            Temukan <strong>kemudahan</strong>, <strong>keuntungan</strong>, dan <strong>peluang usaha</strong> dalam satu aplikasi.
          </p>
          <ul className="mt-4">
             Ayo bergabung sekarang juga
          </ul>
        </div>
      );
      break;
    default:
      narasi = null;
  }

  return narasi ? (
    <div className="bg-white py-6 px-4 shadow-inner">
      {narasi}
    </div>
  ) : null;
}

export default function LandingPage() {
  const [formData, setFormData] = useState({ outlet: "", pemilik: "", alamat: "", pin: "", referral: "" });
  const [errors, setErrors] = useState({});
  const [submitted, setSubmitted] = useState(false);
  const [formValid, setFormValid] = useState(false);
  const [activePage, setActivePage] = useState("Beranda");

  const validateInput = (name, value) => {
    const alphanumeric = /^[a-zA-Z0-9\s]+$/;
    const noSpecial = /^[a-zA-Z0-9]+$/;
    if (!value && name !== "referral") return "Wajib diisi";
    if ((name === "pin" || name === "referral") && value && !noSpecial.test(value)) return "Hanya boleh diisi angka atau huruf";
    if (name === "pin" && value.length > 0 && value.length < 6) return "Pin minimal 6 karakter";
    if (value && !alphanumeric.test(value) && name !== "pin" && name !== "referral") return "Hanya boleh angka atau huruf";
    return "";
  };

  useEffect(() => {
    const newErrors = {};
    let valid = true;
    Object.entries(formData).forEach(([key, value]) => {
      const error = validateInput(key, value);
      if (error) {
        newErrors[key] = error;
        if (key !== "referral") valid = false;
      }
      if (!value && key !== "referral") valid = false;
    });
    setErrors(newErrors);
    setFormValid(valid);
  }, [formData]);

  const handleChange = (e) => {
    const { name, value } = e.target;
    setFormData({ ...formData, [name]: value });
    if (submitted) {
      const error = validateInput(name, value);
      setErrors((prevErrors) => ({ ...prevErrors, [name]: error }));
    }
  };

  const handleSubmit = () => {
    setSubmitted(true);
    if (formValid) {
      const { outlet, pemilik, alamat, pin, referral } = formData;
      const pesan = `DAFTAR#${outlet}#${pemilik}#${alamat}#${pin}#${referral}`;
      const whatsappLink = `https://wa.me/6281354506741?text=${encodeURIComponent(pesan)}`;
      window.open(whatsappLink, "_blank");
    }
  };

  const pages = ["Beranda", "Server", "Aplikasi", "Tentang", "Pendaftaran", "Kontak"];

  const iconMap = {
    outlet: <FiHome className="text-pink-500 text-xl" />,
    pemilik: <FiUser className="text-blue-500 text-xl" />,
    alamat: <FiMapPin className="text-green-500 text-xl" />,
    pin: <FiLock className="text-purple-500 text-xl" />,
    referral: <FiGift className="text-yellow-500 text-xl" />,
  };

  const renderFormInput = (label, name) => (
    <div key={name} className="relative mb-4 animate-fadeIn">
      <label className="block font-semibold text-lg mb-1">{label}</label>
      <div className="relative">
        <div className="absolute left-3 top-3">{iconMap[name]}</div>
        <input
          type="text"
          name={name}
          value={formData[name]}
          onChange={handleChange}
          className={`pl-10 w-full px-4 py-2 border-2 rounded-xl shadow-md transition-all duration-300 focus:outline-none focus:ring-2 focus:ring-yellow-400 ${
            errors[name] ? "border-red-500 animate-shake" : "border-gray-300"
          }`}
        />
      </div>
      {errors[name] && <p className="text-red-600 mt-1 text-sm animate-fadeIn">{errors[name]}</p>}
    </div>
  );

  const renderContent = () => {
    if (activePage === "Pendaftaran") {
      return (
        <section id="pendaftaran" className="py-12 px-6 bg-gray-50">
          <div className="max-w-3xl mx-auto">
            <h2 className="text-2xl md:text-4xl font-bold text-center mb-6">Formulir Pendaftaran</h2>
            <p className="text-center text-l mb-4">
              Isi formulir di bawah ini untuk bergabung menjadi agen resmi Mandiri Cell. Setelah mendaftar, Anda akan mendapatkan akses ke aplikasi Galeri Pulsa dan bisa langsung memulai bisnis digital Anda.
            </p>
            <form className="space-y-4">
              {renderFormInput("Nama Outlet", "outlet")}
              {renderFormInput("Nama Pemilik", "pemilik")}
              {renderFormInput("Alamat Lengkap", "alamat")}
              {renderFormInput("Buat Pin Transaksi", "pin")}
              {renderFormInput("Referral (Optional)", "referral")}
              <button
                type="button"
                onClick={handleSubmit}
                className={`font-bold py-2 px-6 rounded text-black transition-all duration-300 ${
                  formValid ? "bg-yellow-400 hover:bg-yellow-500" : "bg-gray-300 cursor-not-allowed"
                }`}
                disabled={!formValid}
              >
                Daftar Sekarang
              </button>
            </form>
          </div>
        </section>
      );
    }
    return null;
  };

  return (
    <div className="bg-[#00ABDC] text-gray-800 font-sans">
      <style>{`
        @keyframes shake {
          0%, 100% { transform: translateX(0); }
          25% { transform: translateX(-4px); }
          75% { transform: translateX(4px); }
        }
        .animate-shake { animation: shake 0.4s ease; }
        @keyframes fadeIn {
          from { opacity: 0; }
          to { opacity: 1; }
        }
        .animate-fadeIn { animation: fadeIn 0.3s ease-out; }
      `}</style>
      <nav className="bg-white shadow sticky top-0 z-50">
        <div className="max-w-6xl mx-auto px-4 py-2">
          <div className="flex flex-wrap justify-center gap-2 text-sm md:text-base font-medium">
            {pages.map((page) => (
              <a
                key={page}
                href={`#${page.toLowerCase()}`}
                onClick={() => setActivePage(page)}
                className={`px-4 py-2 rounded-full transition-all duration-200 border ${
                  activePage === page ? "bg-yellow-400 text-black border-yellow-500 shadow-md" : "bg-white text-gray-700 border-gray-300 hover:bg-yellow-100 hover:scale-105"
                }`}
              >
                {page}
              </a>
            ))}
          </div>
        </div>
      </nav>

      <header className="bg-yellow-400 text-black p-6 shadow-md">
        <div className="max-w-6xl mx-auto text-center">
          <h1 className="text-3xl md:text-5xl font-bold flex justify-center items-center gap-2">
            <FiZap className="text-4xl animate-pulse" /> Mandiri Cell
          </h1>
          <p className="text-sm md:text-base font-medium mt-1 italic">Solusi Bisnis Pulsa Terpercaya Sejak 2018</p>
          <marquee className="text-base md:text-lg mt-2 font-semibold">
            Mandiri Cell Server Pulsa All Operator | Aplikasi Galeri Pulsa | Sistem Downline Menguntungkan
          </marquee>
        </div>
      </header>

      <NarasiDinamis currentPage={activePage} />
      {renderContent()}

      <footer className="bg-gray-900 text-white text-center py-6 mt-12">
        <p>&copy; {new Date().getFullYear()} Mandiri Cell. All rights reserved.</p>
        <p>WhatsApp: <a href="https://wa.me/6281354506741" className="underline text-yellow-400">6281354506741</a></p>
        <p>Telegram: <a href="https://t.me/CSO_MandiriCell" className="underline text-yellow-400">@CSO_MandiriCell</a></p>
      </footer>
    </div>
  );
}

