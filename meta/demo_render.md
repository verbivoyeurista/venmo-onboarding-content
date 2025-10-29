# Demo Render: Venmo Onboarding Flow

This example shows how text could be pulled dynamically from the content system.

---

**Screen:** `accountAccess`  
- Primary Button → `buttons.createAccount` → “Create account”  
- Secondary Button → `buttons.logIn` → “Log in”

**Next Screen:** `accountType`  
- Header → `accountType.header` → “How will you use Venmo?”
- Option 1 → `accountType.personal.label` → “Personal”
- Option 2 → `accountType.teen.label` → “Teen”
- Option 3 → `accountType.business.label` → “Business”
- CTA → `accountType.buttons.getStarted` → “Get started”

---

This setup lets:
- Designers work with structured content names (`buttons.createAccount`)
- Engineers map them directly into UI components
- Writers update text in one place, system-wide

