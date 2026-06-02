```aura width=800 height=620
<div style={{
  display: 'flex',
  flexDirection: 'column',
  alignItems: 'center',
  width: '100%',
  height: '100%',
  background: '#0B0813',
  borderRadius: '16px',
  padding: '45px 40px',
  boxSizing: 'border-box',
  fontFamily: 'Segoe UI, -apple-system, BlinkMacSystemFont, Roboto, sans-serif',
  position: 'relative',
  overflow: 'hidden',
  border: '1px solid #231633'
}}>
  {/* Cyberpunk Pink & Purple Ambient Orb Glows */}
  <div style={{
    position: 'absolute',
    top: '-40px',
    left: '10%',
    width: '320px',
    height: '320px',
    borderRadius: '50%',
    background: 'radial-gradient(circle, rgba(219,39,119,0.25) 0%, rgba(0,0,0,0) 70%)',
    filter: 'blur(40px)'
  }} />
  <div style={{
    position: 'absolute',
    top: '120px',
    right: '10%',
    width: '320px',
    height: '320px',
    borderRadius: '50%',
    background: 'radial-gradient(circle, rgba(147,51,234,0.25) 0%, rgba(0,0,0,0) 70%)',
    filter: 'blur(40px)'
  }} />

  {/* Technical Corner Brackets */}
  <div style={{ position: 'absolute', top: '20px', left: '20px', width: '16px', height: '16px', borderTop: '2px solid rgba(219,39,119,0.5)', borderLeft: '2px solid rgba(219,39,119,0.5)' }} />
  <div style={{ position: 'absolute', top: '20px', right: '20px', width: '16px', height: '16px', borderTop: '2px solid rgba(147,51,234,0.5)', borderRight: '2px solid rgba(147,51,234,0.5)' }} />
  <div style={{ position: 'absolute', bottom: '20px', left: '20px', width: '16px', height: '16px', borderBottom: '2px solid rgba(147,51,234,0.5)', borderLeft: '2px solid rgba(147,51,234,0.5)' }} />
  <div style={{ position: 'absolute', bottom: '20px', right: '20px', width: '16px', height: '16px', borderBottom: '2px solid rgba(219,39,119,0.5)', borderRight: '2px solid rgba(219,39,119,0.5)' }} />

  {/* ==================== SECTION 1: HEADER & BIO ==================== */}
  <h1 style={{
    color: '#FFFFFF',
    fontSize: '46px',
    fontWeight: '900',
    margin: '10px 0 6px 0',
    letterSpacing: '8px',
    textShadow: '0 0 20px rgba(219,39,119,0.5)'
  }}>
    NEHA PRASAD
  </h1>

  <div style={{
    display: 'flex',
    color: '#E9D5FF',
    fontSize: '12px',
    fontWeight: '600',
    letterSpacing: '4px',
    textTransform: 'uppercase',
    marginBottom: '20px',
    opacity: '0.9'
  }}>
    Data Engineer // MLOps &amp; AI Enthusiast
  </div>

  <div style={{
    display: 'flex',
    color: '#D1D5DB',
    fontSize: '14px',
    lineHeight: '1.6',
    textAlign: 'center',
    maxWidth: '620px',
    marginBottom: '16px',
    fontWeight: '400'
  }}>
    🍒 Hiii! I'm an aspiring Data Engineer and AI/ML enthusiast focused on building scalable data pipelines, streaming architectures, and automating machine learning workflows. Welcome to my tech journey!
  </div>

  <div style={{
    display: 'flex',
    gap: '12px',
    marginBottom: '30px',
    flexWrap: 'wrap',
    justifyContent: 'center'
  }}>
    <div style={{ display: 'flex', background: 'rgba(147, 51, 234, 0.15)', border: '1px solid rgba(147, 51, 234, 0.3)', color: '#E9D5FF', padding: '4px 12px', borderRadius: '4px', fontSize: '11px', fontFamily: 'Consolas, monospace' }}>
      🎓 BSc Data Science @ IIT Madras
    </div>
    <div style={{ display: 'flex', background: 'rgba(219, 39, 119, 0.15)', border: '1px solid rgba(219, 39, 119, 0.3)', color: '#FCE7F3', padding: '4px 12px', borderRadius: '4px', fontSize: '11px', fontFamily: 'Consolas, monospace' }}>
      🎓 B.Tech Computer Science
    </div>
  </div>

  <div style={{ width: '100%', height: '1px', background: 'linear-gradient(90deg, rgba(0,0,0,0) 0%, rgba(255,255,255,0.08) 50%, rgba(0,0,0,0) 100%)', marginBottom: '30px' }} />

  {/* ==================== SECTION 2: DYNAMIC METRICS ==================== */}
  <div style={{
    display: 'flex',
    justifyContent: 'space-around',
    alignItems: 'center',
    width: '90%',
    fontFamily: 'Consolas, monospace',
    marginBottom: '35px'
  }}>
    <div style={{ display: 'flex', flexDirection: 'column', textAlign: 'center', width: '30%' }}>
      <div style={{ color: '#FFFFFF', fontSize: '36px', fontWeight: 'bold', letterSpacing: '-1px' }}>$user.public_repos</div>
      <div style={{ color: '#DB2777', fontSize: '10px', letterSpacing: '2px', textTransform: 'uppercase', marginTop: '6px', fontWeight: '600' }}>Repositories</div>
    </div>
    <div style={{ width: '1px', height: '40px', background: 'rgba(255,255,255,0.05)' }} />
    <div style={{ display: 'flex', flexDirection: 'column', textAlign: 'center', width: '30%' }}>
      <div style={{ color: '#FFFFFF', fontSize: '36px', fontWeight: 'bold', letterSpacing: '-1px' }}>$stats.commits</div>
      <div style={{ color: '#9333EA', fontSize: '10px', letterSpacing: '2px', textTransform: 'uppercase', marginTop: '6px', fontWeight: '600' }}>Commits</div>
    </div>
    <div style={{ width: '1px', height: '40px', background: 'rgba(255,255,255,0.05)' }} />
    <div style={{ display: 'flex', flexDirection: 'column', textAlign: 'center', width: '30%' }}>
      <div style={{ color: '#FFFFFF', fontSize: '36px', fontWeight: 'bold', letterSpacing: '-1px' }}>$stats.stars</div>
      <div style={{ color: '#DB2777', fontSize: '10px', letterSpacing: '2px', textTransform: 'uppercase', marginTop: '6px', fontWeight: '600' }}>Stars</div>
    </div>
  </div>

  {/* ==================== SECTION 3: SOCIALS ABOVE TECH STACK ==================== */}
  <div style={{
    display: 'flex',
    gap: '12px',
    justifyContent: 'center',
    width: '90%',
    marginBottom: '30px'
  }}>
    <a href="[https://linkedin.com/in/18nehaprasad/](https://linkedin.com/in/18nehaprasad/)" target="_blank" style={{ display: 'flex' }}>
      <img src="[https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&amp;logoColor=white](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&amp;logoColor=white)" alt="LinkedIn" />
    </a>
    <a href="mailto:nehap.works@gmail.com" style={{ display: 'flex' }}>
      <img src="[https://img.shields.io/badge/Email-D14836?logo=gmail&amp;logoColor=white](https://img.shields.io/badge/Email-D14836?logo=gmail&amp;logoColor=white)" alt="Email" />
    </a>
  </div>

  {/* ==================== SECTION 4: TECH STACK ANALYTICS ==================== */}
  <div style={{
    display: 'flex',
    color: '#FFFFFF',
    fontSize: '13px',
    fontWeight: '700',
    letterSpacing: '3px',
    textTransform: 'uppercase',
    marginBottom: '20px',
    alignSelf: 'flex-start',
    paddingLeft: '5%',
    fontFamily: 'Consolas, monospace',
    opacity: '0.9'
  }}>
    // TECH STACK ANALYTICS
  </div>

  <div style={{ display: 'flex', flexDirection: 'column', gap: '16px', width: '90%', marginBottom: '25px' }}>
    {/* Row 1: Languages */}
    <div style={{ display: 'flex', flexWrap: 'wrap', gap: '8px', alignItems: 'center' }}>
      <span style={{ color: '#DB2777', fontSize: '11px', fontFamily: 'Consolas, monospace', minWidth: '110px' }}>LANGUAGES &gt;</span>
      <div style={{ display: 'flex', background: 'rgba(35, 22, 51, 0.4)', border: '1px solid rgba(219, 39, 119, 0.15)', color: '#E9D5FF', padding: '4px 12px', borderRadius: '4px', fontSize: '12px', fontFamily: 'Consolas, monospace' }}>Python</div>
      <div style={{ display: 'flex', background: 'rgba(35, 22, 51, 0.4)', border: '1px solid rgba(219, 39, 119, 0.15)', color: '#E9D5FF', padding: '4px 12px', borderRadius: '4px', fontSize: '12px', fontFamily: 'Consolas, monospace' }}>SQL</div>
      <div style={{ display: 'flex', background: 'rgba(35, 22, 51, 0.4)', border: '1px solid rgba(219, 39, 119, 0.15)', color: '#E9D5FF', padding: '4px 12px', borderRadius: '4px', fontSize: '12px', fontFamily: 'Consolas, monospace' }}>JavaScript</div>
      <div style={{ display: 'flex', background: 'rgba(35, 22, 51, 0.4)', border: '1px solid rgba(219, 39, 119, 0.15)', color: '#E9D5FF', padding: '4px 12px', borderRadius: '4px', fontSize: '12px', fontFamily: 'Consolas, monospace' }}>C++</div>
      <div style={{ display: 'flex', background: 'rgba(35, 22, 51, 0.4)', border: '1px solid rgba(219, 39, 119, 0.15)', color: '#E9D5FF', padding: '4px 12px', borderRadius: '4px', fontSize: '12px', fontFamily: 'Consolas, monospace' }}>Java</div>
      <div style={{ display: 'flex', background: 'rgba(35, 22, 51, 0.4)', border: '1px solid rgba(219, 39, 119, 0.15)', color: '#E9D5FF', padding: '4px 12px', borderRadius: '4px', fontSize: '12px', fontFamily: 'Consolas, monospace' }}>Bash</div>
    </div>

    {/* Row 2: Data & MLOps */}
    <div style={{ display: 'flex', flexWrap: 'wrap', gap: '8px', alignItems: 'center' }}>
      <span style={{ color: '#9333EA', fontSize: '11px', fontFamily: 'Consolas, monospace', minWidth: '110px' }}>DATA &amp; MLOPS &gt;</span>
      <div style={{ display: 'flex', background: 'rgba(35, 22, 51, 0.4)', border: '1px solid rgba(147, 51, 234, 0.15)', color: '#E9D5FF', padding: '4px 12px', borderRadius: '4px', fontSize: '12px', fontFamily: 'Consolas, monospace' }}>Docker</div>
      <div style={{ display: 'flex', background: 'rgba(35, 22, 51, 0.4)', border: '1px solid rgba(147, 51, 234, 0.15)', color: '#E9D5FF', padding: '4px 12px', borderRadius: '4px', fontSize: '12px', fontFamily: 'Consolas, monospace' }}>Kubernetes</div>
      <div style={{ display: 'flex', background: 'rgba(35, 22, 51, 0.4)', border: '1px solid rgba(147, 51, 234, 0.15)', color: '#E9D5FF', padding: '4px 12px', borderRadius: '4px', fontSize: '12px', fontFamily: 'Consolas, monospace' }}>Apache Airflow</div>
      <div style={{ display: 'flex', background: 'rgba(35, 22, 51, 0.4)', border: '1px solid rgba(147, 51, 234, 0.15)', color: '#E9D5FF', padding: '4px 12px', borderRadius: '4px', fontSize: '12px', fontFamily: 'Consolas, monospace' }}>DVC</div>
      <div style={{ display: 'flex', background: 'rgba(35, 22, 51, 0.4)', border: '1px solid rgba(147, 51, 234, 0.15)', color: '#E9D5FF', padding: '4px 12px', borderRadius: '4px', fontSize: '12px', fontFamily: 'Consolas, monospace' }}>PostgreSQL</div>
      <div style={{ display: 'flex', background: 'rgba(35, 22, 51, 0.4)', border: '1px solid rgba(147, 51, 234, 0.15)', color: '#E9D5FF', padding: '4px 12px', borderRadius: '4px', fontSize: '12px', fontFamily: 'Consolas, monospace' }}>MongoDB</div>
    </div>

    {/* Row 3: Frameworks */}
    <div style={{ display: 'flex', flexWrap: 'wrap', gap: '8px', alignItems: 'center' }}>
      <span style={{ color: '#DB2777', fontSize: '11px', fontFamily: 'Consolas, monospace', minWidth: '110px' }}>FRAMEWORKS &gt;</span>
      <div style={{ display: 'flex', background: 'rgba(35, 22, 51, 0.4)', border: '1px solid rgba(219, 39, 119, 0.15)', color: '#E9D5FF', padding: '4px 12px', borderRadius: '4px', fontSize: '12px', fontFamily: 'Consolas, monospace' }}>FastAPI</div>
      <div style={{ display: 'flex', background: 'rgba(35, 22, 51, 0.4)', border: '1px solid rgba(219, 39, 119, 0.15)', color: '#E9D5FF', padding: '4px 12px', borderRadius: '4px', fontSize: '12px', fontFamily: 'Consolas, monospace' }}>Django</div>
      <div style={{ display: 'flex', background: 'rgba(35, 22, 51, 0.4)', border: '1px solid rgba(219, 39, 119, 0.15)', color: '#E9D5FF', padding: '4px 12px', borderRadius: '4px', fontSize: '12px', fontFamily: 'Consolas, monospace' }}>Node.js</div>
      <div style={{ display: 'flex', background: 'rgba(35, 22, 51, 0.4)', border: '1px solid rgba(219, 39, 119, 0.15)', color: '#E9D5FF', padding: '4px 12px', borderRadius: '4px', fontSize: '12px', fontFamily: 'Consolas, monospace' }}>TensorFlow</div>
      <div style={{ display: 'flex', background: 'rgba(35, 22, 51, 0.4)', border: '1px solid rgba(219, 39, 119, 0.15)', color: '#E9D5FF', padding: '4px 12px', borderRadius: '4px', fontSize: '12px', fontFamily: 'Consolas, monospace' }}>Scikit-Learn</div>
      <div style={{ display: 'flex', background: 'rgba(35, 22, 51, 0.4)', border: '1px solid rgba(219, 39, 119, 0.15)', color: '#E9D5FF', padding: '4px 12px', borderRadius: '4px', fontSize: '12px', fontFamily: 'Consolas, monospace' }}>Pandas</div>
    </div>
  </div>

  {/* Footer branding text */}
  <div style={{
    position: 'absolute',
    bottom: '25px',
    color: '#4B5563',
    fontSize: '9px',
    letterSpacing: '2px',
    fontFamily: 'Consolas, monospace',
    textTransform: 'uppercase',
    display: 'flex'
  }}>
    Neha Prasad — High Performance Data Infrastructure
  </div>
</div>
```

## 📈 GitHub Metrics
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=nehaprasad1&theme=dark&dark_source=true&hide_border=true&include_all_commits=true&count_private=true&title_color=db2777&icon_color=9333ea&text_color=e9d5ff&bg_color=0b0813" height="180" />
  <img src="https://nirzak-streak-stats.vercel.app/?user=nehaprasad1&theme=tokyonight&hide_border=true&background=0b0813&ring=db2777&fire=9333ea" height="180" />
</p>

### Language Distribution & Contributions
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=nehaprasad1&theme=dark&hide_border=true&include_all_commits=true&count_private=true&layout=compact&title_color=db2777&text_color=e9d5ff&bg_color=0b0813" height="160" />
  <img src="https://github-contributor-stats.vercel.app/api?username=nehaprasad1&limit=5&theme=dark&combine_all_yearly_contributions=true" height="160" />
</p>

---
<p align="right">
  <a href="https://visitcount.itsvg.in"><img src="https://visitcount.itsvg.in/api?id=nehaprasad1&icon=0&color=5" alt="Visits" /></a>
</p>