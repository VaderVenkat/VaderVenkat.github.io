# Venkateshan K.S — Personal Portfolio
### Built with Blazor WebAssembly & C# (.NET 8)

---

## 🚀 Quick Start

### Prerequisites
- [.NET 8 SDK](https://dotnet.microsoft.com/download/dotnet/8.0) — download and install first

### Run Locally
```bash
# 1. Navigate to project folder
cd VenkatPortfolio

# 2. Restore packages
dotnet restore

# 3. Run development server
dotnet run

# 4. Open browser at:
# https://localhost:5001  or  http://localhost:5000
```

---

## 📁 Project Structure

```
VenkatPortfolio/
├── Pages/
│   ├── Index.razor         ← Home page (Hero, Stats, Featured Projects, CTA)
│   ├── About.razor         ← About Me, Education Timeline, Interests
│   ├── Projects.razor      ← Detailed project showcase
│   ├── Skills.razor        ← Skill bars, soft skills, currently learning
│   ├── Awards.razor        ← "Q" Pioneer award with certificate image
│   ├── Contact.razor       ← Contact methods + email form
│   └── Resume.razor        ← Resume download page
│
├── Components/
│   └── SkillBar.razor      ← Reusable C# skill bar component
│
├── Shared/
│   ├── MainLayout.razor    ← Root layout wrapper
│   ├── NavMenu.razor       ← Sticky responsive navbar
│   └── Footer.razor        ← Footer with social links
│
├── wwwroot/
│   ├── css/
│   │   └── app.css         ← Full minimalist stylesheet
│   ├── images/
│   │   ├── war-of-worlds.png
│   │   ├── pandora.png
│   │   └── q-pioneer.jpg
│   ├── resume/
│   │   └── VenkateshanKS_CV.pdf
│   ├── favicon.svg
│   └── index.html          ← Entry HTML with loading screen
│
├── App.razor               ← Router setup
├── _Imports.razor          ← Global using statements
├── Program.cs              ← App entry point
└── VenkatPortfolio.csproj  ← .NET 8 Blazor WASM project file
```

---

## 🎨 Design

- **Theme:** Minimalist · Light / White
- **Accent Color:** `#E84545` (Orange-Red)
- **Font:** Inter (Google Fonts)
- **Icons:** Inline SVG (zero copyright, zero external dependency)
- **Images:** Your own game screenshots + Q Pioneer certificate

---

## 🌐 Deploy to GitHub Pages (Free Hosting)

```bash
# 1. Publish the app
dotnet publish -c Release -o publish

# 2. The output is in /publish/wwwroot/
# Upload this folder to GitHub Pages or any static host
```

### Other free hosting options:
- **Netlify** — drag & drop the `wwwroot` publish folder
- **Vercel** — connect your GitHub repo
- **Firebase Hosting** — `firebase deploy`

> ⚠️ For SPA routing on static hosts, add a `404.html` that redirects to `index.html`

---

## 📄 Pages

| Page | Route | Description |
|------|-------|-------------|
| Home | `/` | Hero, stats, featured projects, CTA |
| About | `/about` | Bio, education timeline, interests |
| Projects | `/projects` | War of the Worlds + Pandora details |
| Skills | `/skills` | Skill bars + currently learning |
| Awards | `/awards` | "Q" Pioneer certificate |
| Contact | `/contact` | All contact methods + email form |
| Resume | `/resume` | Download CV button |

---

## ✏️ How to Update Content

All content is in the `.razor` files under `Pages/`. Just edit the text directly.

To add a new project — copy a project block in `Projects.razor` and update the fields.

---

## 👤 Developer

**Venkateshan K.S**  
Unity Game Developer · Chennai, Tamil Nadu, India  
venkateshanramasamy2001@gmail.com  
[LinkedIn](https://linkedin.com/in/venkateshan-k-s) · [GitHub](https://github.com/VaderVenkat) · [Itch.io](https://vadervenkat.itch.io)
