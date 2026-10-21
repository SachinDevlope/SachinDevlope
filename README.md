<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1412,60:3b2a20,100:c8773a&height=190&section=header&text=Sachin%20Kumar&fontSize=46&fontColor=F5E6D3&fontAlignY=36&desc=Full%20Stack%20Developer%20%C2%B7%20Next.js%20%C2%B7%20React%20%C2%B7%20Node.js%20%C2%B7%20TypeScript&descSize=16&descAlignY=58&animation=fadeIn" width="100%" alt="Sachin Kumar" />

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&pause=1400&color=E8A15A&center=true&vCenter=true&width=620&lines=Full+Stack+Developer+at+Nav+Jyoti+Metals;Building+a+manufacturing+ERP+two+companies+use+daily;298+reads+down+to+16.+Still+proud.;Next.js,+React,+Node.js,+TypeScript,+Firestore" alt="typing" />
</p>

```bash
$ whoami
Sachin Kumar — Full Stack Developer, Ghaziabad, India

$ cat now.txt
Building Nav Jyoti ERP: an in-house manufacturing ERP for a cable and wire plant,
used every day by two companies for HR, production, purchase, inventory, dispatch and email.
Before this: full stack apps at ReqX Technologies (EduFix, Hometown Hub).

$ cat how.txt
Read the logs. Measure. Fix. Measure again. Ship with the numbers.

$ ./coffee --status
refilling (always)
```

### $ tree nav-jyoti-erp

```
nav-jyoti-erp/
├── hr/           recruitment pipeline, joining form, offer letters, employee master, leaves, holidays
├── attendance/   eSSL X2008 biometric punches over ADMS, through a Cloudflare Worker proxy
│                 daily / monthly / 92-day views, Excel export, A4 print, one machine per company
├── production/   DPR entry for 4 lines (Cable, DPC Wire, DPC Strip, SE Wire), plan vs actual, incentives
├── purchase/     GRN split across POs, return to vendor, approval-gated quantity corrections on FIFO stock
├── dispatch/     route planner: suggested trucks and Google routes from open dispatch instructions
├── prices/       daily metal rates from NALCO, Hindalco, BALCO, Westmetall and Vedanta's LME mail
├── email/        a Gmail client inside the ERP: sync, filing by customer / vendor / desk, threaded replies
└── backup/       resumable chunked uploads of the document archive to Google Drive
```

<sub>Next.js 14 · TypeScript · Firestore · NextAuth · Cloudflare Workers · Vercel. Built on a work account, which is why this profile's graph looks like I'm on holiday. I'm not.</sub>

### $ git log --fixes

```diff
- the DPR screen read 298 work orders to show 16, and every save waited on a 7–60 s recompute
+ reads narrowed to the line, writes in parallel, recompute moved to the background with waitUntil
+ page load 1.79 s → 0.68 s (−62%) · save reads 1.6 s → 0.57 s (−64%) · output identical · 4 lines

- one missed morning punch turned every following day into a half day
+ staff punches paired by calendar date; night-shift pairing kept for factory labour

- two companies reused the same employee codes, so a punch could land on the wrong person
+ each biometric machine tied to its company; refused and unknown devices logged

- counting a thread's messages fetched every message body, up to 0.5 MB each, on every synced mail
+ one count aggregation; fourteen one-by-one mailbox reads became a single query

- one vendor address copied on 3,361 unrelated threads filed every one of them as Vendor
+ filing matches on the sender only
```

### $ cat stack

<p align="left">
  <img src="https://skillicons.dev/icons?i=nextjs,react,nodejs,ts,js,express,mongodb,postgres,prisma,firebase,tailwind,jest,vercel,git&theme=dark&perline=7" alt="stack" />
</p>

### $ ls side-projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/SachinDevlope/STRATEGY-AI">Strategy-AI</a></h3>
      Resume builder and analyzer on Groq: ATS-friendly PDF, match score, skill gaps, interview prep. It reviewed my resume too. We don't talk about the score.<br/><br/>
      <img src="https://skillicons.dev/icons?i=nextjs,ts,mongodb,vercel&theme=dark" height="32" alt="stack" /><br/><br/>
      <a href="https://strategy-ai-lac.vercel.app"><b>Live demo</b></a> · <a href="https://github.com/SachinDevlope/STRATEGY-AI">Code</a>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/SachinDevlope/Tracker">Tracker</a></h3>
      Attendance, expenses, debts and tiffin in one PWA. Imports bank statement PDFs and lets an LLM work out where the money went.<br/><br/>
      <img src="https://skillicons.dev/icons?i=nextjs,react,mongodb,tailwind&theme=dark" height="32" alt="stack" /><br/><br/>
      <a href="https://github.com/SachinDevlope/Tracker"><b>Code</b></a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/SachinDevlope/EduFix">EduFix</a></h3>
      School facility issue portal: JWT auth, RBAC for 4 roles, Jest tests. The broken fan finally gets a ticket number.<br/><br/>
      <img src="https://skillicons.dev/icons?i=nextjs,ts,mongodb,jest&theme=dark" height="32" alt="stack" /><br/><br/>
      <a href="https://github.com/SachinDevlope/EduFix"><b>Code</b></a>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/SachinDevlope/Hometown">Hometown Hub</a></h3>
      Community platform on PostgreSQL and Prisma: communities, feed, comments, events. Relatives asking about salary not included.<br/><br/>
      <img src="https://skillicons.dev/icons?i=nextjs,ts,postgres,prisma&theme=dark" height="32" alt="stack" /><br/><br/>
      <a href="https://github.com/SachinDevlope/Hometown"><b>Code</b></a>
    </td>
  </tr>
</table>

### $ ping sachin

<p align="left">
  <a href="mailto:sachin.devlope@gmail.com"><img src="https://skillicons.dev/icons?i=gmail&theme=dark" height="40" alt="Email" /></a>&nbsp;
  <a href="https://www.linkedin.com/in/sachin-kumar-1a18461b1"><img src="https://skillicons.dev/icons?i=linkedin&theme=dark" height="40" alt="LinkedIn" /></a>&nbsp;
  <a href="https://strategy-ai-lac.vercel.app"><img src="https://skillicons.dev/icons?i=vercel&theme=dark" height="40" alt="Live project" /></a>
</p>

`sachin.devlope@gmail.com` · open to Full Stack / MERN / Next.js roles

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:c8773a,40:3b2a20,100:1a1412&height=100&section=footer" width="100%" alt="footer" />
