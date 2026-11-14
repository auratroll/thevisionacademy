# The Vision Academy

*Learn Today, Lead Tomorrow.* Class 9 se 12 ke students ke liye study material, results aur online MCQ tests.

## Pages
- `index.html`: home aur study material
- `test.html`: **Online Test Session**. Student sign in karke class-wise MCQ test deta hai, timer chalta hai aur result foran milta hai.
- `admin.html`: admin panel (news, Drive links, maintenance, **Test Session Manager**, students)
- `result.html`, `supplystuff.html`, `about.html`, `contact.html`

## Test Session: admin ke liye
1. `admin.html` par apne admin email aur password se login karein.
2. **Create / Edit Test**: title, subject, class aur time likhein. MCQs paste karein ya `.txt/.csv/.json` file select karein, phir **Load MCQs** dabayein. Format ke liye `sample-mcqs.txt` dekhein.
3. **Save & Publish Test** dabayein. Test usi waqt us class ke students ko dikhne lagega.
4. **Manage Tests** mein test ki class dropdown se badlein, Publish/Hide karein, Edit, Copy ya Delete karein.
5. **Student Results** mein har test ki ranking dekhein aur CSV export karein.

## Firebase setup (zaroori, sirf ek baar)
`firestore.rules` file ka content Firebase Console → Firestore Database → **Rules** mein paste karke **Publish** karein.
