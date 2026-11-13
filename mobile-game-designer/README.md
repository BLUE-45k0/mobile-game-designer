# mobile-game-designer

مهارة (Skill) لـ Claude تساعد في تصميم وتشخيص ألعاب الموبايل اعتماداً على خلاصة أبحاث «كيف تصمم لعبة موبايل ممتعة لا يُمل منها». تغطي: الحلقة الأساسية، التقدم والاقتصاد، تشخيص الاحتفاظ (D1/D7/D30)، Onboarding وFTUE، الإعلانات المكافئة، LiveOps، إحساس اللعب، اختبار اللعب، ومراجعة GDD.

**مبدأ المهارة:** كل رقم يُذكر مع مصدره وتحذيره المنهجي، وتُميَّز الحقائق عن التقديرات وعن ادعاءات الجهات التجارية. لا أرقام من خارج المصدر.

## التثبيت

### Claude.ai
1. نزّل `mobile-game-designer.zip` (أو اضغط مجلد `mobile-game-designer` بحيث يكون `SKILL.md` داخل المجلد مباشرة).
2. من **Settings ← Capabilities (أو Skills)** اختر رفع Skill وارفع الملف.
3. فعّل المهارة.

### Claude Code
```bash
git clone <repo-url>
mkdir -p ~/.claude/skills
cp -r mobile-game-designer ~/.claude/skills/
```
(أو في مجلد `.claude/skills/` داخل مشروعك.)

## أمثلة استخدام

- «لعبتي puzzle وD7 فيها 6%، ما الخطوات؟»
- «D1 في لعبتي match على Android منخفض، كيف أشخّص؟»
- «كم عدد الإعلانات المكافئة المناسبة في الجلسة؟»
- «راجع هذا الـ GDD لحلقة لعب روغلايت»
- «جهّز لي بروتوكول اختبار صامت لنموذجي الأولي»

## شجرة الملفات

```
mobile-game-designer/
├── SKILL.md
├── README.md
├── LICENSE
├── references/
│   ├── 00-overview.md
│   ├── 01-retention-benchmarks.md
│   ├── 02-psychology.md
│   ├── 03-infinite-gameplay.md
│   ├── 04-mobile-ux-game-feel.md
│   ├── 05-longterm-retention-monetization.md
│   ├── 06-case-studies.md
│   ├── 07-implementation-roadmap.md
│   └── extras.md
└── templates/
    ├── gray-box-test-checklist.md
    ├── silent-playtest-protocol.md
    ├── retention-diagnosis.md
    └── telemetry-plan.md
```

## ملاحظة عن المصدر

كل المحتوى في `references/` (عدا `extras.md`) مستمد من مستند الأبحاث المرفق. `extras.md` يحتوي فقط إضافات عامة غير مستمدة منه، وهي معلَّمة كذلك.

## الترخيص

MIT — انظر `LICENSE`.
