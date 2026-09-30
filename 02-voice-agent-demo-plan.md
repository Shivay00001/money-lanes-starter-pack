# AI Voice Agent — 48-Hour Demo Plan

Goal: ek 60-second ka demo jo Upwork/Fiverr proposals me lagake $500–2,000 wale jobs jeete.
(Buyer demand verified Aug–Sept 2026: $2,000 fixed healthcare build, $500 clinic receptionist.)

## Demo app (local, tested) — READY
`~/workspace/money-lanes/ai-receptionist-demo/receptionist.py`
- Offline rule-based brain + optional Gemini free-tier key
- Fictional client: "Bright Smile Dental" (Sydney) — hamare dental outreach niche se match
- `--demo` flag scripted conversation chalata hai (Loom recording ke liye perfect)

Run: `cd ~/workspace/money-lanes/ai-receptionist-demo && python3 receptionist.py --demo`

## Phone-side steps (Day 1–2)
1. **Vapi.ai** → free tier signup → ek inbound assistant banao (system prompt: dental receptionist — booking, hours, emergency triage)
2. **Twilio trial** → free trial number lo (trial credit milta hai) → Vapi se connect karo
3. Khud call karke test karo: "Hi, I need a cleaning appointment Saturday" → booking flow check
4. **Loom** (free) → 60-sec screen recording: call lagate hue + agent ka jawab + booking confirm
5. Demo video ka link Upwork/Fiverr/Contra profile me dalo

## Proposal angle (Upwork — profile live hone ke baad)
- Subject: "AI receptionist for [clinic] — 60-sec demo attached"
- Body: 3 lines — kya banaya, kis stack pe (Vapi + Twilio), demo link
- Price anchor: $500 pilot (research me $500 wala job 50+ proposals ke saath bhi hire hua — demo differentiate karta hai)

## Rules (research se)
- Low-end $30 wale postings trap hain — skip
- Client ke Vapi/Twilio minutes ka kharcha CLIENT dega — kabhi khud absorb mat karo
- Pehla review sabse mushkil gate hai — pehle 2 clients ko thoda undercut ok, uske baad rate badhao
