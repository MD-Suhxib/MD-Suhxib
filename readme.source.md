```aura width=800 height=240 link="https://github.com/YOUR_USERNAME"
<div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', justifyContent: 'center', width: '100%', height: '100%', background: '#08080c', borderRadius: 20, padding: 30, fontFamily: 'Inter, sans-serif', position: 'relative', overflow: 'hidden', border: '1px solid rgba(110,80,220,0.18)' }}>
  <style>
    {`
      @keyframes pf-drift-r { 0%, 100% { transform: translate(0, 0); opacity: 0.8; } 50% { transform: translate(60px, -14px); opacity: 1; } }
      @keyframes pf-drift-l { 0%, 100% { transform: translate(0, 0); opacity: 0.75; } 50% { transform: translate(-60px, 12px); opacity: 1; } }
      @keyframes pf-pulse { 0%, 100% { transform: scale(1); opacity: 0.8; } 50% { transform: scale(1.2); opacity: 0.5; } }
      #pf-g1 { animation: pf-drift-r 7s ease-in-out infinite; }
      #pf-g2 { animation: pf-drift-l 8.5s ease-in-out infinite; }
      #pf-g3 { animation: pf-pulse 6s ease-in-out infinite; }
      #pf-g4 { animation: pf-drift-r 9s ease-in-out infinite 0.4s; }
      #pf-g5 { animation: pf-drift-l 7.5s ease-in-out infinite 0.2s; }
    `}
  </style>
  <svg width="800" height="240" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="pfg1" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(110,20,210,0.6)" />
        <stop offset="70%" stopColor="rgba(110,20,210,0)" />
      </radialGradient>
      <radialGradient id="pfg2" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(40,70,255,0.5)" />
        <stop offset="70%" stopColor="rgba(40,70,255,0)" />
      </radialGradient>
      <radialGradient id="pfg3" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(255,50,180,0.45)" />
        <stop offset="70%" stopColor="rgba(255,50,180,0)" />
      </radialGradient>
      <radialGradient id="pfg4" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(0,160,255,0.4)" />
        <stop offset="70%" stopColor="rgba(0,160,255,0)" />
      </radialGradient>
      <radialGradient id="pfg5" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(160,30,255,0.45)" />
        <stop offset="70%" stopColor="rgba(160,30,255,0)" />
      </radialGradient>
    </defs>
    <ellipse id="pf-g1" cx="150" cy="230" rx="200" ry="90" fill="url(#pfg1)" />
    <ellipse id="pf-g2" cx="650" cy="240" rx="190" ry="90" fill="url(#pfg2)" />
    <ellipse id="pf-g3" cx="400" cy="20" rx="170" ry="70" fill="url(#pfg3)" />
    <ellipse id="pf-g4" cx="720" cy="20" rx="150" ry="70" fill="url(#pfg4)" />
    <ellipse id="pf-g5" cx="80" cy="20" rx="150" ry="70" fill="url(#pfg5)" />
  </svg>
  <div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', zIndex: 10 }}>
    <span style={{ fontSize: 14, color: '#a0a0b8', letterSpacing: 3, textTransform: 'uppercase' }}>Hi, I'm</span>
    <span style={{ fontSize: 44, fontWeight: 700, color: 'white', marginTop: 6 }}>Mohammed Suhaib S</span>
    <span style={{ fontSize: 18, color: '#c8b8ff', marginTop: 8 }}>Software Developer · Bangalore, India</span>
  </div>
  <div style={{ display: 'flex', gap: 8, marginTop: 22, zIndex: 10 }}>
    <span style={{ padding: '4px 14px', background: 'rgba(12,10,20,0.6)', color: '#7eb8ff', borderRadius: 12, fontSize: 12, border: '1px solid rgba(120,80,220,0.25)' }}>Building software</span>
    <span style={{ padding: '4px 14px', background: 'rgba(12,10,20,0.6)', color: '#e8c8ff', borderRadius: 12, fontSize: 12, border: '1px solid rgba(120,80,220,0.25)' }}>Always learning</span>
    <span style={{ padding: '4px 14px', background: 'rgba(12,10,20,0.6)', color: '#a0a0ff', borderRadius: 12, fontSize: 12, border: '1px solid rgba(120,80,220,0.25)' }}>Open to collaborate</span>
  </div>
</div>
```

## About Me

I'm **Mohammed Suhaib S**, a software developer based in **Bangalore, India**. I enjoy turning ideas into clean, reliable software and picking up new tools along the way.

- Currently working as a Software Developer
- Always exploring new technologies and better ways to build things
- Open to collaborations, ideas and good conversations

```aura width=700 height=60 link="https://github.com/YOUR_USERNAME?tab=repositories"
<div style={{ display: 'flex', gap: 10, padding: '12px 20px', width: '100%', height: '100%', background: '#08080c', borderRadius: 30, alignItems: 'center', justifyContent: 'center', fontFamily: 'Inter, sans-serif', position: 'relative', overflow: 'hidden', border: '1px solid rgba(110,80,220,0.18)' }}>
  <style>
    {`
      @keyframes ts-drift-right { 0%, 100% { transform: translate(0, 0); opacity: 0.8; } 50% { transform: translate(40px, -6px); opacity: 1.1; } }
      @keyframes ts-drift-left { 0%, 100% { transform: translate(0, 0); opacity: 0.75; } 50% { transform: translate(-40px, 6px); opacity: 1; } }
      #ts-glow-1 { animation: ts-drift-right 7.5s ease-in-out infinite; }
      #ts-glow-2 { animation: ts-drift-left 8.3s ease-in-out infinite; }
    `}
  </style>
  <svg width="700" height="60" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="tsg1" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(110,20,210,0.55)" />
        <stop offset="70%" stopColor="rgba(110,20,210,0)" />
      </radialGradient>
      <radialGradient id="tsg2" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(40,70,255,0.5)" />
        <stop offset="70%" stopColor="rgba(40,70,255,0)" />
      </radialGradient>
    </defs>
    <ellipse id="ts-glow-1" cx="200" cy="60" rx="180" ry="50" fill="url(#tsg1)" />
    <ellipse id="ts-glow-2" cx="520" cy="60" rx="180" ry="50" fill="url(#tsg2)" />
  </svg>
  <span style={{ padding: '4px 14px', background: 'rgba(12,10,20,0.6)', color: '#f7df1e', borderRadius: 16, fontSize: 13, fontWeight: 600, border: '1px solid rgba(120,80,220,0.2)', zIndex: 10 }}>JavaScript</span>
  <span style={{ padding: '4px 14px', background: 'rgba(12,10,20,0.6)', color: '#7eb8ff', borderRadius: 16, fontSize: 13, fontWeight: 600, border: '1px solid rgba(120,80,220,0.2)', zIndex: 10 }}>TypeScript</span>
  <span style={{ padding: '4px 14px', background: 'rgba(12,10,20,0.6)', color: '#7ee7ff', borderRadius: 16, fontSize: 13, fontWeight: 600, border: '1px solid rgba(120,80,220,0.2)', zIndex: 10 }}>React</span>
  <span style={{ padding: '4px 14px', background: 'rgba(12,10,20,0.6)', color: '#9ee79e', borderRadius: 16, fontSize: 13, fontWeight: 600, border: '1px solid rgba(120,80,220,0.2)', zIndex: 10 }}>Node.js</span>
  <span style={{ padding: '4px 14px', background: 'rgba(12,10,20,0.6)', color: '#ffd878', borderRadius: 16, fontSize: 13, fontWeight: 600, border: '1px solid rgba(120,80,220,0.2)', zIndex: 10 }}>Python</span>
  <span style={{ padding: '4px 14px', background: 'rgba(12,10,20,0.6)', color: '#ffb088', borderRadius: 16, fontSize: 13, fontWeight: 600, border: '1px solid rgba(120,80,220,0.2)', zIndex: 10 }}>SQL</span>
  <span style={{ padding: '4px 14px', background: 'rgba(12,10,20,0.6)', color: '#e8c8ff', borderRadius: 16, fontSize: 13, fontWeight: 600, border: '1px solid rgba(120,80,220,0.2)', zIndex: 10 }}>Git</span>
</div>
```

## Let's Connect

```aura width=130 height=44 link="https://github.com/YOUR_USERNAME" inline align=center
<div style={{ display: 'flex', alignItems: 'center', justifyContent: 'center', width: '100%', height: '100%', background: 'linear-gradient(135deg, #0b0b14, #16102b)', borderRadius: 14, fontFamily: 'Inter, sans-serif', border: '1px solid rgba(130,100,255,0.45)' }}>
  <span style={{ fontSize: 14, fontWeight: 700, color: '#fafafa' }}>GitHub</span>
</div>
```
```aura width=130 height=44 link="https://www.linkedin.com/in/YOUR_LINKEDIN" inline align=center
<div style={{ display: 'flex', alignItems: 'center', justifyContent: 'center', width: '100%', height: '100%', background: 'linear-gradient(135deg, #07101c, #0a2040)', borderRadius: 14, fontFamily: 'Inter, sans-serif', border: '1px solid rgba(60,140,255,0.45)' }}>
  <span style={{ fontSize: 14, fontWeight: 700, color: '#fafafa' }}>LinkedIn</span>
</div>
```
```aura width=130 height=44 link="mailto:YOUR_EMAIL@example.com" inline align=center
<div style={{ display: 'flex', alignItems: 'center', justifyContent: 'center', width: '100%', height: '100%', background: 'linear-gradient(135deg, #0d0008, #1a0012)', borderRadius: 14, fontFamily: 'Inter, sans-serif', border: '1px solid rgba(220,60,120,0.45)' }}>
  <span style={{ fontSize: 14, fontWeight: 700, color: '#fafafa' }}>Email me</span>
</div>
```

<br/>

<p align="center"><sub>Made with <a href="https://www.npmjs.com/package/readme-aura">readme-aura</a></sub></p>