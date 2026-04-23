# Commit Messages

## Commit Message kyun important hai?
- Employers GitHub pe commit history dekhte hain
- Team ko samajh aata hai kya aur kyun change hua
- Baad mein khud bhi samajh aata hai apna code

---

## Bad vs Good Commit

Bad:

	fix a bug

Good:

	Add missing link and alt text to company logo
	Screen readers won't read images to users with disabilities without this 
	information.

---

## Commit Message Structure

### Subject
- Ek line mein kya kiya
- **50 characters** ideal, **72 characters** hard limit
- Active voice use karo → "Fix bug" not "Fixed bug"

### Body
- Kyun kiya — problem kya thi
- Subject se ek blank line ka gap rakhna
- **72 characters** pe wrap karo
- WHAT aur WHY likho — HOW nahi

---

## 7 Rules of a Great Commit Message

1. **Subject aur body ko blank line se separate karo**
2. **Subject line 50 characters tak rakho** (hard limit 72)
3. **Subject line capital letter se shuru karo**
4. **Subject line period (.) se mat khatam karo**
5. **Imperative mood use karo** ("Fix bug" not "Fixed bug")
6. **Body ko 72 characters pe wrap karo**
7. **Body mein WHAT aur WHY likho, HOW nahi**

> [!tip] Imperative Mood Test
> "If applied, this commit will **your subject here**"
> ✅ "If applied, this commit will Fix login bug"
> ❌ "If applied, this commit will Fixed login bug"

---

## Multi-line Commit kaise kare
```bash
git commit
# VS Code mein tab khulega
# Subject likho → blank line → body likho
# Save + close → commit ho jaayega
```

---

## Kab Commit kare?
- Jab koi feature kaam karne lage ✅
- Jab bug fix ho ✅
- Jab typo fix ho ✅
- **Commit early and often!**

> [!summary] Best Practices
> - Active voice, imperative mood use karo
> - Vague messages avoid karo ("saved", "updated")
> - Subject 50 chars ideal, 72 hard limit
> - Body mein "kyun" explain karo