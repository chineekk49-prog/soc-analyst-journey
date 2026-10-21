# Escalation Matrix

| Severity | Жишээ | Acknowledge SLA | Tier 1 хийх зүйл | Escalate хийх хүн | Escalation rule |
|---|---|---:|---|---|---|
| Critical | Ransomware, domain admin compromise | 15 мин | Host-ийг тусгаарлаж, нотолгоо хадгална | Tier 2 + IR lead | Шууд escalate хийнэ |
| High | New admin user, impossible travel | 30 мин | 5W1H шалгаж, IOC-г бусад host дээр шалгана | Tier 2 | 1 цагт шийдэгдэхгүй бол |
| Medium | Suspicious PowerShell | 4 цаг | Playbook-ийн дагуу шалгана | Шаардлагатай бол Tier 2 | - |
| Low | Internal port scan | 24 цаг | Шалгаж, шаардлагатай бол tuning хийнэ | - | - |
