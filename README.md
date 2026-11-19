# Profil_by_-satriaramadhan-
<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Profil Perusahaan</title>
<meta name="description" content="Profil perusahaan: tentang kami, layanan, tim, dan kontak.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:wght@500;700;800&family=Public+Sans:wght@400;500;600&display=swap" rel="stylesheet">
<style>
:root{
  --ink:#101828; --indigo:#1B2A6B; --saffron:#F2B705; --mist:#DDE3EE; --paper:#F5F7FA; --muted:#4A5568;
  --display:"Bricolage Grotesque","Segoe UI",Arial,sans-serif;
  --body:"Public Sans","Segoe UI",Arial,sans-serif;
}
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{font-family:var(--body);color:var(--ink);background:var(--paper);line-height:1.65;font-size:1.0625rem}
a{color:inherit}
:focus-visible{outline:3px solid var(--saffron);outline-offset:3px}
.wrap{max-width:1080px;margin:0 auto;padding:0 24px}

/* Navigasi */
header{position:sticky;top:0;z-index:10;background:var(--paper);border-bottom:1px solid var(--mist)}
header .wrap{display:flex;justify-content:space-between;align-items:center;min-height:64px;gap:16px;flex-wrap:wrap}
.logo{font-family:var(--display);font-weight:800;font-size:1.25rem;text-decoration:none;color:var(--indigo)}
nav ul{list-style:none;display:flex;gap:24px;flex-wrap:wrap}
nav a{text-decoration:none;font-weight:500;padding:4px 0;border-bottom:2px solid transparent}
nav a:hover{border-color:var(--saffron)}

/* Hero */
.hero{padding:72px 0 88px}
.hero .wrap{display:grid;grid-template-columns:1.35fr 1fr;gap:48px;align-items:center}
h1{font-family:var(--display);font-weight:800;font-size:clamp(2.5rem,6.5vw,4.75rem);line-height:1.02;letter-spacing:-.025em;color:var(--indigo)}
.hero p{margin-top:24px;max-width:46ch;color:var(--muted);font-size:1.2rem}
.btn{display:inline-block;margin-top:32px;padding:14px 28px;background:var(--indigo);color:#fff;text-decoration:none;font-weight:600;border-radius:4px;transition:background .2s}
.btn:hover{background:var(--ink)}
.art{position:relative;aspect-ratio:1/1;max-width:420px;width:100%;justify-self:end}
.art span{position:absolute;display:block}
.art .a{inset:0 22% 22% 0;background:var(--indigo);border-radius:50% 0 0 0}
.art .b{inset:22% 0 0 22%;background:var(--saffron);border-radius:0 0 50% 0}
.art .c{inset:36% 36% 36% 36%;background:var(--paper);border-radius:50%}

/* Seksi */
section{padding:72px 0;border-top:1px solid var(--mist)}
h2{font-family:var(--display);font-weight:700;font-size:clamp(1.75rem,3.5vw,2.5rem);line-height:1.15;letter-spacing:-.015em;margin-bottom:32px;color:var(--indigo)}
.cols{display:grid;grid-template-columns:1fr 1fr;gap:48px}
.cols p+p{margin-top:16px}
.cols p{max-width:62ch;color:var(--muted)}
.facts{list-style:none;border-left:4px solid var(--saffron);padding-left:24px}
.facts li{padding:8px 0}
.facts strong{display:block;font-family:var(--display);font-size:1.15rem}

/* Layanan */
.services{list-style:none}
.services li{display:grid;grid-template-columns:minmax(180px,1fr) 2fr;gap:24px;padding:24px 0;border-bottom:1px solid var(--mist)}
.services li:first-child{border-top:1px solid var(--mist)}
.services h3{font-family:var(--display);font-size:1.35rem}
.services p{color:var(--muted);max-width:60ch}

/* Tim */
.team{list-style:none;display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:32px}
.team li{border-top:4px solid var(--indigo);padding-top:16px}
.team strong{display:block;font-family:var(--display);font-size:1.2rem}
