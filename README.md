<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1412,60:3b2a20,100:c8773a&height=190&section=header&text=Sachin%20Kumar&fontSize=46&fontColor=F5E6D3&fontAlignY=36&desc=building.%20breaking.%20learning.&descSize=18&descAlignY=58&animation=fadeIn" width="100%" alt="Sachin Kumar" />

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=17&pause=1800&color=E8A15A&center=true&vCenter=true&width=560&lines=full+stack+developer,+ghaziabad;self-taught,+log-reading,+coffee-powered;an+ERP+by+day,+small+tools+by+night;engineer+in+progress" alt="typing" />
</p>

I'm a full stack developer in Ghaziabad. Self-taught. I learned by building things, breaking them, and reading the logs until they made sense.

Most days I work on a manufacturing ERP that two companies run on. Nights, I build small tools for my own life, usually because I wanted an answer nobody else was going to give me. Like where my salary went.

### how i work

- The logs are usually right. I'm usually wrong first. That's fine, it's faster than guessing.
- "Feels faster" is not a number. 1.79 s → 0.68 s is a number.
- A fix ships with proof: output verified identical on live data, or it doesn't ship.
- Small commits, plain-English messages. Future me is the reader, and he's tired.
- If I need a tool, I build it, then I actually use it.

### the work

```
nav-jyoti-erp/          what two companies run on every day
├── hr + attendance     recruitment, offer letters, leaves; biometric punches over ADMS via a Cloudflare Worker
├── production          DPR entry for 4 lines, plan vs actual, incentive scheme
├── purchase            GRN split across POs, returns to vendor, approval-gated stock corrections
├── dispatch + prices   truck route planner; daily metal rates from NALCO, Hindalco, BALCO, Westmetall, LME
└── email               a Gmail client inside the ERP: sync, filing by customer / vendor / desk, threaded replies
```

Numbers I can back up:

- A report screen read **298 work orders to show 16**. Now it reads 16. Page load **1.79 s → 0.68 s**, and saves stopped waiting on a 7–60 s recompute. Rolled out to 4 production lines.
- One missed morning punch used to turn **every following day into a half day**. It doesn't anymore. Payroll noticed before I did.
- **3,361 email threads** were filed under one vendor because that vendor was CC'd on them. Filing now looks at who actually wrote.

<sub>Next.js 14 · TypeScript · Firestore · NextAuth · Cloudflare Workers · Vercel. Built on a work account, so this profile's graph is only the night-time stuff.</sub>

### stack

<p align="left">
  <img src="https://skillicons.dev/icons?i=nextjs,react,nodejs,ts,js,express,mongodb,postgres,prisma,firebase,tailwind,jest,vercel,git&theme=dark&perline=7" alt="stack" />
</p>

### things i built for myself, then put online

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/SachinDevlope/STRATEGY-AI">Strategy-AI</a></h3>
      I needed a resume reviewer that wouldn't be polite about it. So I built one. Resume builder plus analyzer on Groq: match score, skill gaps, interview prep.<br/><br/>
      <img src="https://skillicons.dev/icons?i=nextjs,ts,mongodb,vercel&theme=dark" height="32" alt="stack" /><br/><br/>
      <a href="https://strategy-ai-lac.vercel.app"><b>Live</b></a> · <a href="https://github.com/SachinDevlope/STRATEGY-AI">Code</a>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/SachinDevlope/Tracker">Tracker</a></h3>
      I wanted to know where my salary went. Now I know. I'm not happier, but I know. Attendance, expenses, debts and tiffin in one PWA, with bank statement import.<br/><br/>
      <img src="https://skillicons.dev/icons?i=nextjs,react,mongodb,tailwind&theme=dark" height="32" alt="stack" /><br/><br/>
      <a href="https://github.com/SachinDevlope/Tracker"><b>Code</b></a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/SachinDevlope/EduFix">EduFix</a></h3>
      School facility issue portal. JWT auth, RBAC for 4 roles, Jest tests. The broken fan finally gets a ticket number.<br/><br/>
      <img src="https://skillicons.dev/icons?i=nextjs,ts,mongodb,jest&theme=dark" height="32" alt="stack" /><br/><br/>
      <a href="https://github.com/SachinDevlope/EduFix"><b>Code</b></a>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/SachinDevlope/Hometown">Hometown Hub</a></h3>
      A community platform for people who left home and still think about it. Communities, feed, events, on PostgreSQL and Prisma.<br/><br/>
      <img src="https://skillicons.dev/icons?i=nextjs,ts,postgres,prisma&theme=dark" height="32" alt="stack" /><br/><br/>
      <a href="https://github.com/SachinDevlope/Hometown"><b>Code</b></a>
    </td>
  </tr>
</table>

### status

```bash
$ status
focusing

$ learning
system design, and how to say "it depends" with a straight face

$ coffee
refilling
```

### say hi

<p align="left">
  <a href="mailto:sachin.devlope@gmail.com"><img src="https://skillicons.dev/icons?i=gmail&theme=dark" height="40" alt="Email" /></a>&nbsp;
  <a href="https://www.linkedin.com/in/sachin-kumar-1a18461b1"><img src="https://skillicons.dev/icons?i=linkedin&theme=dark" height="40" alt="LinkedIn" /></a>&nbsp;
  <a href="https://strategy-ai-lac.vercel.app"><img src="https://skillicons.dev/icons?i=vercel&theme=dark" height="40" alt="Live project" /></a>
</p>

`sachin.devlope@gmail.com` · open to Full Stack / MERN / Next.js roles

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:c8773a,40:3b2a20,100:1a1412&height=100&section=footer" width="100%" alt="footer" />
