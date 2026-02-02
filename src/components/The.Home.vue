<template>
  <v-app class="bio-twist-app">
    <v-app-bar flat color="white" height="80" class="px-md-10">
      <v-img
        src="/IMG_8285.jpg"
        alt="Bio Twist Logo"
        max-width="80"
        contain
        class="mr-3"
      ></v-img>

      <v-spacer></v-spacer>
      <div class="d-none d-md-flex gap-4">
        <v-btn variant="text" href="#home" class="nav-btn">Home</v-btn>
        <v-btn variant="text" href="#problem" class="nav-btn">Why Us?</v-btn>
        <v-btn variant="text" href="#product" class="nav-btn">Product</v-btn>
        <v-btn variant="text" href="#video-demo" class="nav-btn">Demo</v-btn>
        <v-btn variant="text" href="#contact" class="nav-btn">Contact</v-btn>
      </div>
      <v-app-bar-nav-icon class="d-md-none"></v-app-bar-nav-icon>
    </v-app-bar>

    <v-main class="main-content">
      <section id="home" class="hero-section">
        <v-container class="fill-height">
          <v-row align="center" justify="space-between">
            <v-col cols="12" md="6" class="text-center text-md-left">
              <h1 class="hero-title">
                Safe for your family,<br>
                <span class="highlight">gentle on the environment</span>
              </h1>
              <p class="hero-subtitle my-4">
                ตาข่ายล้างจานจากใยสับปะรด & ใยมะพร้าว<br>
                <span class="text-body-1 text-grey">นวัตกรรมเปลี่ยนขยะเหลือทิ้งให้เป็นผลิตภัณฑ์รักษ์โลก</span>
              </p>
              <v-btn 
                color="#A8C680" 
                size="x-large" 
                class="cta-button text-white px-8" 
                rounded="xl" 
                elevation="2"
              >
                Shop Now
              </v-btn>
            </v-col>
            
            <v-col cols="12" md="6" class="position-relative d-flex justify-center">
              <div class="mascot-wrapper">
                <img 
                  src="/IMG_8214.PNG" 
                  alt="Bio Twist Main Mascot" 
                  class="mascot-img rounded-xl" 
                />

                <img 
                  src="/MagicEraser_5690112_205655.PNG"  
                  alt="Mascot Left" 
                  class="mascot-mini-deco left-deco cover" 
                />

                <img 
                  src="/MagicEraser_5690202_225056.PNG" 
                  alt="Mascot Right" 
                  class="mascot-mini-deco right-deco cover" 
                />
              </div>
            </v-col>
          </v-row>
        </v-container>
      </section>
      
      <section id="problem" class="problem-section py-16">
        <v-container>
          <div class="text-center mb-10">
            <h2 class="section-title">The Hidden Problems</h2>
            <p class="text-grey" style="font-size: 1.2rem; font-weight: 500;">
              สิ่งที่คุณอาจมองข้ามในห้องครัวและสิ่งแวดล้อม
            </p>
          </div>

          <v-row justify="center" align="stretch" class="gap-4 gap-md-0">
            <v-col cols="12" md="6" class="d-flex">
              <v-card class="problem-card pa-6 w-100" elevation="2" rounded="xl">
                <img 
                  src="/IMG_8288.jpg" 
                  alt="Dirty Sponge Problem" 
                  class="w-100 rounded-lg mb-4" 
                  style="object-fit: cover; height: 300px;"
                />
                
                <div class="d-flex align-center mb-4">
                  <div class="problem-icon bg-red-lighten-4 text-red-darken-2 mr-4">🦠</div>
                  <h3 class="text-h5 font-weight-bold text-red-darken-3">Kitchen Hygiene</h3>
                </div>
                <p class="text-body-1 text-grey-darken-2">
                  <span class="font-weight-bold">ฟองน้ำเก่า = แหล่งสะสมเชื้อโรค</span><br>
                  งานวิจัยจาก Furtwangen University พบว่าฟองน้ำล้างจานที่ใช้แล้ว
                  เป็นที่อยู่ของแบคทีเรียมากถึง <span class="text-red font-weight-bold">362 สายพันธุ์</span> 
                  เนื่องจากโครงสร้างรูพรุนที่กักเก็บความชื้น
                </p>
              </v-card>
            </v-col>

            <v-col cols="12" md="6" class="d-flex">
              <v-card class="problem-card pa-6 w-100" elevation="2" rounded="xl">
                <img 
                  src="/IMG_8289.jpg" 
                  alt="Agricultural Waste Problem" 
                  class="w-100 rounded-lg mb-4" 
                  style="object-fit: cover; height: 300px;"
                />

                <div class="d-flex align-center mb-4">
                  <div class="problem-icon bg-orange-lighten-4 text-orange-darken-2 mr-4">🍂</div>
                  <h3 class="text-h5 font-weight-bold text-orange-darken-4">Agricultural Waste</h3>
                </div>
                <p class="text-body-1 text-grey-darken-2">
                  <span class="font-weight-bold">ขยะเหลือทิ้งมหาศาล</span><br>
                  การปลูกสับปะรดในไทยสร้างขยะจากใบเหลือทิ้งกว่า 
                  <span class="text-orange-darken-3 font-weight-bold">2.7 ตันต่อปี</span> 
                  รวมถึงเปลือกมะพร้าวที่มักถูกกำจัดด้วยการเผา ก่อให้เกิดมลพิษทางอากาศ
                </p>
              </v-card>
            </v-col>
          </v-row>
        </v-container>
      </section>

      <section id="product" class="product-section py-16">
        <v-container>
          <h2 class="section-title text-center mb-10">The Natural Solution</h2>
          
          <v-row justify="center" align="start" class="product-grid-row">
            
            <v-col cols="12" md="4" class="d-flex justify-center">
              <v-card class="product-card soft-side" width="320" elevation="4">
                <v-card-text class="text-center">
                  <div class="icon-emoji">🍍</div>
                  <h3 class="text-h5 font-weight-bold mt-2 text-primary-green">Pineapple Fiber</h3>
                  <p class="text-caption text-grey font-weight-bold">SOFT SIDE (General Wiping)</p>
                  <v-divider class="my-3"></v-divider>
                  <v-list density="compact" class="text-left">
                    <v-list-item prepend-icon="mdi-feather" title="Smooth touch" subtitle="ผิวสัมผัสนุ่ม ไม่ระคายเคือง"></v-list-item>
                    <v-list-item prepend-icon="mdi-water-outline" title="Highly absorbent" subtitle="ซึมซับน้ำได้ดีเยี่ยม"></v-list-item>
                    <v-list-item prepend-icon="mdi-sparkles" title="Gentle cleansing" subtitle="ไม่ทิ้งรอยขีดข่วนบนภาชนะ"></v-list-item>
                  </v-list>
                </v-card-text>
              </v-card>
            </v-col>

            <v-col cols="12" md="4" class="d-flex justify-center align-center py-10 py-md-0">
               <div class="product-showcase">
                  <div class="circle-bg"></div>
                  <img 
                    src="/IMG_8287.jpg" 
                    alt="Bio Twist Product Mockup" 
                    class="mockup-img elevation-6 rounded-xl"
                  />
               </div>
            </v-col>

            <v-col cols="12" md="4" class="d-flex justify-center">
              <v-card class="product-card hard-side" width="320" elevation="4">
                <v-card-text class="text-center">
                  <div class="icon-emoji">🥥</div>
                  <h3 class="text-h5 font-weight-bold mt-2 text-brown">Coconut Fiber</h3>
                  <p class="text-caption text-grey font-weight-bold">SCRUB SIDE (Heavy Stains)</p>
                  <v-divider class="my-3"></v-divider>
                  <v-list density="compact" class="text-left">
                    <v-list-item prepend-icon="mdi-dumbbell" title="Durable & Scrubbing" subtitle="เส้นใยทนทาน ขจัดคราบหนัก"></v-list-item>
                    <v-list-item prepend-icon="mdi-weather-windy" title="Quick drying" subtitle="แห้งไว ลดการสะสมเชื้อโรค"></v-list-item>
                    <v-list-item prepend-icon="mdi-shield-check" title="Water resistance" subtitle="ทนทานต่อน้ำ ไม่เปื่อยง่าย"></v-list-item>
                  </v-list>
                </v-card-text>
              </v-card>
            </v-col>

          </v-row>
        </v-container>
      </section>

      <section class="features-section py-12 bg-primary-green">
        <v-container>
          <v-row justify="center" align="start">
            <v-col cols="6" md="2" class="text-center feature-item">
              <div class="feature-icon">♻️</div>
              <p class="font-weight-bold text-white mt-3">100%<br>Biodegradable</p>
            </v-col>
            <v-col cols="6" md="2" class="text-center feature-item">
              <div class="feature-icon">🦠</div>
              <p class="font-weight-bold text-white mt-3">Bacteria &<br>Mold Free</p>
            </v-col>
            <v-col cols="6" md="2" class="text-center feature-item">
              <div class="feature-icon">🌬️</div>
              <p class="font-weight-bold text-white mt-3">Keeps Dry<br>& Odorless</p>
            </v-col>
            <v-col cols="6" md="2" class="text-center feature-item">
              <div class="feature-icon">🌿</div>
              <p class="font-weight-bold text-white mt-3">Non-Toxic<br>Chemical Free</p>
            </v-col>
            <v-col cols="6" md="2" class="text-center feature-item">
              <div class="feature-icon">🇹🇭</div>
              <p class="font-weight-bold text-white mt-3">Support<br>Thai Farmers</p>
            </v-col>
          </v-row>
        </v-container>
      </section>
    </v-main>

    <v-footer id="contact" color="#333" class="text-center d-flex flex-column py-10">
      <v-img
        src="/IMG_8285.jpg"
        alt="Bio Twist Logo"
        width="100"
        max-width="100"
        contain
        class="mb-4 rounded-lg"
      ></v-img>
      
      <h3 class="text-primary-green mb-2">Bio Twist</h3>
      <p class="text-grey-lighten-1">แปรรูปขยะจากมะพร้าวและสับปะรด สร้างงาน สร้างอาชีพ</p>
      <v-divider class="my-4 w-50 border-opacity-25"></v-divider>
      <p class="text-caption text-grey">© 2026 Bio Twist. All rights reserved.</p>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  name: 'TheHome',
  data() {
    return {
      //
    }
  }
}
</script>

<style scoped>
/* Font Setup */
@import url('https://fonts.googleapis.com/css2?family=Prompt:wght@300;400;600;700&display=swap');

.bio-twist-app {
  font-family: 'Prompt', sans-serif !important;
  background-color: #F9F9F4 !important;
}

/* --- Custom Colors --- */
.text-primary-green { color: #A8C680 !important; }
.bg-primary-green { background-color: #A8C680 !important; }
.text-brown { color: #8D6E63 !important; }

/* --- Navbar --- */
.logo {
  font-size: 1.8rem;
  font-weight: 800;
  color: #A8C680;
  letter-spacing: 1px;
}

.nav-btn {
  text-transform: capitalize;
  font-weight: 600;
  color: #555;
}

/* --- Hero Section --- */
.hero-section {
  min-height: 85vh;
  background: radial-gradient(circle at top right, #e8f5e9 0%, transparent 45%);
  display: flex;
  align-items: center;
}

.hero-title {
  font-size: 3.5rem;
  line-height: 1.2;
  color: #4A4A4A;
  font-weight: 700;
}

.highlight {
  color: #A8C680;
}

.hero-subtitle {
  font-size: 1.7rem;
  color: #654a25;
  font-weight: bold;
}

/* --- Mascot Wrapper & Decorations --- */
.mascot-wrapper {
  position: relative;
  width: 100%;
  max-width: 650px; 
  margin-bottom: 20px;
}

.mascot-img {
  width: 100%;
  height: auto;
  z-index: 2;
  position: relative;
  filter: drop-shadow(0 10px 15px rgba(0,0,0,0.1));
}

.mascot-mini-deco {
  position: absolute;
  width: 130px;    
  height: 130px;
  object-fit: contain;
  z-index: 3;
  bottom: -40px;
  transition: transform 0.3s ease;
  /* เพิ่ม Shadow เล็กน้อยเพื่อให้ดูลอย */
  filter: drop-shadow(0 5px 10px rgba(0,0,0,0.15));
}

.mascot-mini-deco:hover {
  transform: scale(1.1);
}

.left-deco {
  left: -10px;
  transform: rotate(-10deg);
}

.right-deco {
  right: -10px;
  transform: rotate(10deg);
}

/* --- Problem Section --- */
.section-title {
  font-size: 2.5rem;
  font-weight: bold;
  color: #4A4A4A;
}

.problem-card {
  border: 1px solid #e0e0e0;
  transition: transform 0.3s;
  height: 100%;
  display: flex;
  flex-direction: column;
}

.problem-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 10px 20px rgba(0,0,0,0.08) !important;
}

.problem-icon {
  width: 50px;
  height: 50px;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 1.5rem;
}

/* --- Product Section --- */
.product-section {
  background-color: #F9F9F4;
}

.product-card {
  border-top: 6px solid #A8C680;
  border-radius: 16px;
  transition: transform 0.3s;
}

.product-card:hover {
  transform: translateY(-5px);
}

.product-card.hard-side {
  border-top-color: #8D6E63;
}

.icon-emoji {
  font-size: 3.5rem;
}

/* --- Product Showcase (Center Image) --- */
.product-showcase {
  display: flex;
  align-items: center;
  justify-content: center;
  position: relative;
  width: 100%;
  /* ปรับความสูงพื้นที่โชว์สินค้าให้รองรับรูปใหญ่ */
  height: 350px; 
}

.circle-bg {
  position: absolute;
  /* วงกลมพื้นหลังใหญ่ขึ้น */
  width: 380px;
  height: 380px;
  background-color: #fff;
  border-radius: 50%;
  z-index: 1;
  box-shadow: 0 10px 30px rgba(0,0,0,0.05);
}

.mockup-img {
  /* รูปสินค้าใหญ่ขึ้น */
  width: 320px;
  height: 320px;
  object-fit: contain;
  position: relative;
  z-index: 2;
  
  
}

/* --- Video Section --- */
.video-frame-wrapper {
  position: relative;
  padding-bottom: 56.25%; /* 16:9 Aspect Ratio */
  height: 0;
  overflow: hidden;
  background: #000;
  border: 8px solid #fff; 
  box-shadow: 0 15px 40px rgba(0,0,0,0.15);
}

.video-iframe {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}

/* --- Features Section --- */
.feature-icon {
  font-size: 3rem;
  background: rgba(255,255,255,0.2);
  width: 90px;
  height: 90px;
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 50%;
  margin: 0 auto;
}

/* --- Footer --- */
.mascot-mini {
  font-size: 2.5rem;
  margin-bottom: 0.5rem;
}

/* --- Responsive Breakpoints --- */
@media (max-width: 960px) {
  .hero-title {
    font-size: 2.5rem;
  }
  
  /* ปรับขนาด Mascot ในมือถือ */
  .mascot-mini-deco {
    width: 80px;
    height: 80px;
    bottom: -20px;
  }
  
  /* ปรับขนาด Product Showcase ในมือถือ */
  .product-showcase {
    height: 300px;
    margin-top: 2rem;
    margin-bottom: 2rem;
  }
  .circle-bg {
    width: 280px;
    height: 280px;
  }
  .mockup-img {
    width: 240px;
    height: 240px;
  }
}
</style>