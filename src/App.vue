<template>
  <div id="app">
    <h1>CV Saya</h1>
    <section id="Tentang saya">
      <h2>Tentang saya</h2>
       <p>DZIKRI FITRA HANDRIAN.</p>
      <p>Saya adalah seorang mahasiswa teknik informatika. Saya mempelajari Software Engineer dan Web Developer.
        Saya memiliki keahlian dalam pengembangan web. Saya adalah seorang yang bersemangat dalam mempelajari teknologi baru dan selalu ingin meningkatkan kemampuan saya. 
        Saya juga senang bekerja sama dengan tim dan membantu orang lain. Saya juga menguasai sedikit tentang jaringan dan cctv.</p>
    </section>
    <section id="education">
      <h2>Pendidikan</h2>
      <ul>
      SD,SMP,SMK, sedang menjalani masa kuliah
        <li>
          <h3>Nama Gelar</h3>
          <p>JAWIR</p>
          <h4>Universitas</h4>
          <p>Universitas Islam Riau</p>

          <h5>Awal Tahun - Akhir Tahun</h5>
          <p>2022 - 2029</p>
        </li>
        </ul>
    </section>
    <section id="experience">
      <h2>Pengalaman</h2>
      <ul>
      Mengelola ip cctv
        <li>
          <h3>Job Title</h3>
          <p>Teknisi Cctv</p>
          <h4>Nama Perusahaan</h4>
          <p>Bintang Cctv</p>
          <h5>Tanggal Mulai - Tanggal Berakhir</h5>
          <p>15/01/2021 - 25/06/2021</p>
          <ul>
            <li>Saya memiliki tanggung jawab atas perbaikan cctv tersebut</li>
            </ul>
        </li>
        </ul>
    </section>
    <section id="skills">
      <h2>Skills</h2>
      <p>Mengubungkan ip cctv</p>
      <ul>
        <li>Skill 1</li>
        <p>Memasang cctv</p>
        <li>Skill 2</li>
        <p>Membetulkan DvD Cctv</p>
        </ul>
    </section>
    <section id="contact">
      <h2>Contact</h2>
      <ul>
        <li>Email: dzikrifitra23@gmail.com</li>
        </ul>
    </section>
  </div>
</template>

<script>
export default {
  name: 'App'
};
</script>


/* General Styles */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f5f5f5; /* Light gray background */
}

#app {
  max-width: 800px; /* Set a maximum width for responsiveness */
  margin: 2rem auto; /* Auto-center the content */
  padding: 2rem;
  background-color: #fff; /* White background for content area */
  border-radius: 5px; /* Rounded corners for a polished look */
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); /* Subtle shadow for depth */
}

h1, h2 {
  margin: 0 0 1rem; /* Add some bottom margin for headings */
}

h1 {
  font-size: 2em;
  color: #333; /* Darker heading color */
  text-align: center;
}

h2 {
  font-size: 1.5em;
  color: #666; /* Slightly lighter heading color */
}

p, ul {
  margin: 0 0 1rem;
  line-height: 1.5; /* Improve readability with line spacing */
}

ul {
  list-style: none; /* Remove default bullet points */
  padding: 0;
}

li {
  margin-bottom: 0.5rem;
}
 

/* Section Styles */
section {
  margin-bottom: 2rem; /* Add some spacing between sections */
}

#about-me p {
  color: #888; /* More subdued text color for introduction */
}

#education ul,
#experience ul,
#skills ul {
  padding-left: 1.5rem; /* Indent list items for clarity */
}

#education h3,
#experience h3,
#skills li {
  font-weight: bold; /* Emphasize titles and skills */
}

#experience ul li ul {
  margin-left: 2rem; /* Further indent nested responsibilities list */
  list-style: disc; /* Use disc bullets for sub-items */
}

/* Contact Styles */
#contact ul {
  display: flex; /* Arrange contact info side-by-side */
  flex-wrap: wrap; /* Allow items to wrap on smaller screens */
}

#contact li {
  margin-right: 1rem;
  flex: 1; /* Distribute space equally between contact items */
}

#contact li:last-child {
  margin-right: 0; /* Remove margin from last item */
}