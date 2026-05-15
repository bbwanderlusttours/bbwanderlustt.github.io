<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>BB Wanderlust Tours — Africa · Europe · Beyond</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,600;1,300;1,400&family=Cinzel:wght@400;600;700&family=Lato:wght@300;400&display=swap" rel="stylesheet">

<script>
/* ── TRANSLATIONS ── */
const T = {
  en: {
    nav_about: "About",
    nav_services: "Services",
    nav_destinations: "Destinations",
    nav_story: "Our Story",
    nav_book: "Book",
    nav_cta: "Plan My Trip",
    hero_eyebrow: "Africa · Europe · Beyond",
    hero_title1: "Where Two",
    hero_title2: "Continents Unite",
    hero_sub: "Your authentic bridge between Ghana & Italy — curated journeys, real connections, lifelong memories.",
    hero_btn1: "Start Your Journey",
    hero_btn2: "Our Story",
    hero_scroll: "Scroll",
    strip: ["✈ Flight Booking","🏨 Luxury Accommodation","🗺 Expert Tour Guide","🌍 Ghana · Italy · Africa · Europe","🦁 Safari Experiences","🍝 Cultural Immersion","🏖 Beach Resorts"],
    about_label: "About Us",
    about_title1: "Meet Your",
    about_title2: "Bridge",
    about_title3: "Between Worlds",
    about_badge_top: "2",
    about_badge_bot: "Continents\nOne Guide",
    about_quote: '"My European friends wanted Africa. My African friends wanted Europe. I realized I could be the bridge."',
    about_p1: 'My name is <strong>Nana Ofori (Cyril)</strong>, founder of BB Wanderlust Tours. Born in Ghana, raised across Italy, I have spent nearly a decade navigating two of the world\'s most beautiful cultures — and I want to share that gift with you.',
    about_p2: 'What sets BB Wanderlust apart is lived experience. I don\'t just know the tourist spots — I know the <strong>hidden markets, authentic restaurants, local families, and breathtaking corners</strong> that most travellers never discover.',
    about_p3: 'In just three weeks, we explored 5 regions of Ghana and discovered that behind every fear was a greater discovery. That is the BB Wanderlust promise.',
    about_btn: "Book a Consultation",
    svc_label: "What We Offer",
    svc_title1: "Our",
    svc_title2: "Services",
    svc_sub: "End-to-end travel support — from your first search to your last sunset. Every service is personalized, every journey is yours.",
    svc1_title: "Flight Booking", svc1_p: "We find the most affordable and convenient flights between Africa and Europe, including connecting routes, best stopovers, and price alerts to save you money.",
    svc2_title: "Accommodation", svc2_p: "From boutique guesthouses to luxury beach resorts — we match accommodation to your exact budget and preferences, whether you crave comfort, culture, or both.",
    svc3_title: "Private Tour Guide", svc3_p: "With Cyril as your guide, experience destinations the way locals do. Skip the tourist traps and discover the real Ghana, Italy, and beyond.",
    svc4_title: "Safari & Adventures", svc4_p: "Wildlife safaris, Lamborghini drives, mountain escapes, deep sea fishing, cultural festivals — we curate extraordinary experiences across Africa.",
    svc5_title: "Business Travel", svc5_p: "Connecting entrepreneurs across continents. We facilitate business trips, trade missions, and networking opportunities between African and European markets.",
    svc6_title: "Cultural Immersion", svc6_p: "Food tours, local markets, traditional ceremonies, street life, coastal villages — immerse yourself in the authentic heartbeat of each destination.",
    dest_label: "Destinations",
    dest_title1: "Two Continents,",
    dest_title2: "Infinite Possibilities",
    dest_all: "All", dest_africa: "Africa 🌍", dest_europe: "Europe 🏛️",
    dest_note: "And many more destinations across both continents — ask Cyril about your dream location.",
    dest1_name:"Accra, Ghana", dest1_sub:"The Heart of West Africa",
    dest2_name:"Rome, Italy", dest2_sub:"The Eternal City",
    dest3_name:"Safari, Kenya", dest3_sub:"Wild Africa Awaits",
    dest4_name:"Amalfi Coast", dest4_sub:"Italy's Jewel Shore",
    dest5_name:"Cape Town, SA", dest5_sub:"Where Oceans Meet",
    dest6_name:"Florence, Italy", dest6_sub:"Art, Culture & Renaissance",
    exp_label: "Experiences",
    exp_title1: "Beyond the",
    exp_title2: "Ordinary",
    exp1_title:"Lamborghini & Supercar Drives, Ghana", exp1_p:"Experience the thrill of luxury supercars through Accra's scenic routes — a bucket-list moment few expect in West Africa.",
    exp2_title:"Ghana Regional Road Trip — 5 Regions", exp2_p:"Follow the route Cyril and his Italian friend pioneered: breathtaking landscapes, vibrant culture, waterfalls, and warm local hospitality.",
    exp3_title:"Coastal Beach Resorts & Private Islands", exp3_p:"From Ghana's pristine Atlantic coast to Italy's Amalfi and Sardinia — the world's finest coastlines, curated for you.",
    exp4_title:"Local Street Food & Hidden Market Tours", exp4_p:"From kelewele in Kumasi to carbonara in Trastevere — food is the gateway to any culture, and we know every table worth sitting at.",
    exp5_title:"Italian Art, History & Architecture", exp5_p:"Florence, Venice, Rome — we go beyond the guidebook into the stories behind the art and the people who made history.",
    story_label: "The BB Wanderlust Story",
    story_title1: "Born From",
    story_title2: "Two Worlds",
    story_p1: "The idea for BB Wanderlust was born from a simple but powerful observation: European friends always asked me to take them to Ghana, while African friends repeatedly asked me to invite them to Italy.",
    story_p2: 'Since my life had always been between these two continents, I realized something special — I could be the bridge that connects people through <em style="color:var(--gold-light);">travel, culture, and unforgettable experiences.</em>',
    story_p3: "The first journey back to Ghana changed everything. Even I, who knew the language and the people, arrived with uncertainty after years away. What we found was beyond imagination: breathtaking landscapes, vibrant culture, warm people, amazing food, and adventure around every corner.",
    story_p4: '<em style="color:var(--gold-light);">"Behind every fear was an even greater discovery."</em>',
    stat1_label:"Regions Explored", stat2_label:"Continents Covered", stat3_label:"Memories Created", stat4_label:"Passionate Guide",
    tl1_title:"Born in Ghana", tl1_p:"Nana Ofori (Cyril) grows up immersed in Ghanaian culture, community, and the warmth of West Africa.",
    tl2_title:"Nearly a Decade in Italy", tl2_p:"Living, working and exploring Italy — mastering the language, culture, cuisine, and discovering Europe's hidden corners.",
    tl3_title:"The Journey That Changed Everything", tl3_p:"Cyril returns to Ghana with an Italian friend. In 3 weeks, 5 regions, they discover what most travellers never see.",
    tl4_title:"BB Wanderlust Tours Is Born", tl4_p:"With a mission to connect continents through authentic travel, BB Wanderlust launches — the world needs this bridge.",
    tl5_title:"Your Adventure Begins", tl5_p:"Every journey Cyril guides carries the same passion, energy, and commitment to showing people the world as it truly is.",
    book_label: "Let's Plan Together",
    book_title1: "Book Your",
    book_title2: "Dream Journey",
    book_intro: "Fill out the form below and Cyril will personally reach out within 24 hours to craft your perfect itinerary.",
    form_fname:"First Name *", form_lname:"Last Name *", form_email:"Email Address *", form_phone:"WhatsApp / Phone",
    form_direction:"Travel Direction *", form_dir_ph:"Select your route",
    form_dir1:"Europe → Ghana / Africa", form_dir2:"Ghana / Africa → Italy / Europe", form_dir3:"Within Africa", form_dir4:"Within Europe", form_dir5:"Custom Route",
    form_service:"Service Needed *", form_svc_ph:"What do you need?",
    form_svc1:"Flights Only", form_svc2:"Accommodation Only", form_svc3:"Tour Guide Only", form_svc4:"Flights + Accommodation", form_svc5:"Full Package (Flights + Stay + Guide)", form_svc6:"Custom Experience",
    form_date:"Approximate Travel Date", form_travellers:"Number of Travellers",
    form_t1:"Solo (1)", form_t2:"Couple (2)", form_t3:"Small Group (3–5)", form_t4:"Group (6–10)", form_t5:"Large Group (10+)",
    form_budget:"Budget Range (per person)", form_budget_ph:"Approximate budget",
    form_b1:"Under €500 / $500", form_b2:"€500 – €1,500", form_b3:"€1,500 – €3,000", form_b4:"€3,000 – €5,000", form_b5:"€5,000+ (Luxury)", form_b6:"Flexible — surprise me",
    form_heard:"How did you find us?", form_heard_ph:"Select one",
    form_h1:"Instagram", form_h2:"Friend / Referral", form_h3:"Google Search", form_h4:"Other Social Media", form_h5:"Other",
    form_msg:"Tell us about your dream trip *", form_msg_ph:"Describe your ideal experience — places you want to see, things you want to do, any special requests or occasions we should know about...",
    form_submit:"✦ Send My Enquiry ✦",
    form_note:"📧 Enquiries are sent to bbwanderlusttours@gmail.com — expect a reply within 24 hours.",
    success_title:"✦ Enquiry Received! ✦",
    success_p:"Thank you for reaching out to BB Wanderlust Tours. Cyril will personally review your enquiry and get back to you within 24 hours.<br><br>In the meantime, follow us on Instagram <strong>@bb_wanderlust_tours</strong> for travel inspiration!",
    social_label:"Follow the Journey",
    social_sub:"See the world through Cyril's lens — real adventures, real moments.",
    social_ig:"Follow us on Instagram for travel inspiration, destination guides & behind-the-scenes adventures",
    social_btn:"Follow on Instagram",
    footer_brand:"BB Wanderlust Tours — the authentic bridge between Ghana & Italy, Africa & Europe. Built on lived experience, driven by passion.",
    footer_svc:"Services", footer_dest:"Destinations", footer_contact:"Contact",
    footer_svc1:"Flight Booking", footer_svc2:"Accommodation", footer_svc3:"Tour Guide", footer_svc4:"Safari & Adventure", footer_svc5:"Business Travel",
    footer_dest1:"Ghana", footer_dest2:"Italy", footer_dest3:"Kenya", footer_dest4:"South Africa", footer_dest5:"And More…",
    footer_c1:"📧 Email Us", footer_c2:"📸 Instagram", footer_c3:"📝 Book Now",
    footer_copy:"© 2025 BB Wanderlust Tours · All Rights Reserved · Nana Ofori (Cyril)",
  },
  it: {
    nav_about: "Chi Siamo",
    nav_services: "Servizi",
    nav_destinations: "Destinazioni",
    nav_story: "La Nostra Storia",
    nav_book: "Prenota",
    nav_cta: "Pianifica il Viaggio",
    hero_eyebrow: "Africa · Europa · Oltre",
    hero_title1: "Dove Due",
    hero_title2: "Continenti Si Incontrano",
    hero_sub: "Il tuo ponte autentico tra Ghana e Italia — viaggi curati, connessioni reali, ricordi per tutta la vita.",
    hero_btn1: "Inizia il Tuo Viaggio",
    hero_btn2: "La Nostra Storia",
    hero_scroll: "Scorri",
    strip: ["✈ Prenotazione Voli","🏨 Alloggio di Lusso","🗺 Guida Turistica Esperta","🌍 Ghana · Italia · Africa · Europa","🦁 Esperienze Safari","🍝 Immersione Culturale","🏖 Resort Balneari"],
    about_label: "Chi Siamo",
    about_title1: "Incontra il Tuo",
    about_title2: "Ponte",
    about_title3: "Tra i Mondi",
    about_badge_top: "2",
    about_badge_bot: "Continenti\nUna Guida",
    about_quote: '"I miei amici europei volevano l\'Africa. I miei amici africani volevano l\'Europa. Ho capito che potevo essere il ponte."',
    about_p1: 'Mi chiamo <strong>Nana Ofori (Cyril)</strong>, fondatore di BB Wanderlust Tours. Nato in Ghana, cresciuto in Italia, ho trascorso quasi un decennio navigando tra due delle culture più belle del mondo — e voglio condividere questo dono con te.',
    about_p2: 'Ciò che distingue BB Wanderlust è l\'esperienza vissuta. Non conosco solo i luoghi turistici — conosco i <strong>mercati nascosti, i ristoranti autentici, le famiglie locali e gli angoli mozzafiato</strong> che la maggior parte dei viaggiatori non scopre mai.',
    about_p3: 'In sole tre settimane abbiamo esplorato 5 regioni del Ghana e scoperto che dietro ogni paura si nascondeva una scoperta ancora più grande. Questa è la promessa di BB Wanderlust.',
    about_btn: "Prenota una Consulenza",
    svc_label: "Cosa Offriamo",
    svc_title1: "I Nostri",
    svc_title2: "Servizi",
    svc_sub: "Supporto di viaggio completo — dalla prima ricerca all'ultimo tramonto. Ogni servizio è personalizzato, ogni viaggio è tuo.",
    svc1_title:"Prenotazione Voli", svc1_p:"Troviamo i voli più convenienti tra Africa ed Europa, inclusi percorsi in connessione, scali ottimali e avvisi di prezzo per farti risparmiare.",
    svc2_title:"Alloggio", svc2_p:"Da boutique hotel a resort balneari di lusso — abbiniamo l'alloggio al tuo budget e alle tue preferenze esatte, che tu voglia comfort, cultura o entrambi.",
    svc3_title:"Guida Turistica Privata", svc3_p:"Con Cyril come guida, vivi le destinazioni come i locali. Evita le trappole turistiche e scopri il vero Ghana, l'Italia autentica e oltre.",
    svc4_title:"Safari & Avventure", svc4_p:"Safari nella natura, gite in Lamborghini, fughe in montagna, pesca d'altura, festival culturali — curiamo esperienze straordinarie in tutta l'Africa.",
    svc5_title:"Viaggi d'Affari", svc5_p:"Connettere imprenditori tra i continenti. Facilitiamo viaggi d'affari, missioni commerciali e opportunità di networking tra i mercati africani ed europei.",
    svc6_title:"Immersione Culturale", svc6_p:"Tour gastronomici, mercati locali, cerimonie tradizionali, vita di strada, villaggi costieri — immergiti nel battito autentico di ogni destinazione.",
    dest_label: "Destinazioni",
    dest_title1: "Due Continenti,",
    dest_title2: "Infinite Possibilità",
    dest_all:"Tutte", dest_africa:"Africa 🌍", dest_europe:"Europa 🏛️",
    dest_note: "E molte altre destinazioni in entrambi i continenti — chiedi a Cyril della tua destinazione dei sogni.",
    dest1_name:"Accra, Ghana", dest1_sub:"Il Cuore dell'Africa Occidentale",
    dest2_name:"Roma, Italia", dest2_sub:"La Città Eterna",
    dest3_name:"Safari, Kenya", dest3_sub:"L'Africa Selvaggia Ti Aspetta",
    dest4_name:"Costa Amalfitana", dest4_sub:"Il Gioiello della Costa Italiana",
    dest5_name:"Città del Capo, SA", dest5_sub:"Dove Si Incontrano gli Oceani",
    dest6_name:"Firenze, Italia", dest6_sub:"Arte, Cultura & Rinascimento",
    exp_label: "Esperienze",
    exp_title1: "Oltre",
    exp_title2: "l'Ordinario",
    exp1_title:"Lamborghini & Supercar in Ghana", exp1_p:"Vivi il brivido delle supercar di lusso lungo le strade panoramiche di Accra — un momento da sogno che pochi si aspettano nell'Africa Occidentale.",
    exp2_title:"Road Trip nelle 5 Regioni del Ghana", exp2_p:"Segui il percorso inaugurato da Cyril e dal suo amico italiano: paesaggi mozzafiato, cultura vibrante, cascate e calorosa ospitalità locale.",
    exp3_title:"Resort Balneari e Isole Private", exp3_p:"Dalla costa atlantica incontaminata del Ghana all'Amalfi e alla Sardegna — le coste più belle del mondo, curate per te.",
    exp4_title:"Street Food Locale e Tour dei Mercati Nascosti", exp4_p:"Dallo kelewele di Kumasi alla carbonara di Trastevere — il cibo è la porta d'accesso a ogni cultura, e noi conosciamo ogni tavola che vale la pena di sedersi.",
    exp5_title:"Arte, Storia e Architettura Italiana", exp5_p:"Firenze, Venezia, Roma — andiamo oltre la guida turistica per entrare nelle storie dell'arte e dei personaggi che hanno fatto la storia.",
    story_label: "La Storia di BB Wanderlust",
    story_title1: "Nata da",
    story_title2: "Due Mondi",
    story_p1: "L'idea di BB Wanderlust è nata da un'osservazione semplice ma potente: gli amici europei mi chiedevano sempre di portarli in Ghana, mentre gli amici africani mi chiedevano ripetutamente di invitarli in Italia.",
    story_p2: 'Poiché la mia vita è sempre stata tra questi due continenti, ho realizzato qualcosa di speciale — potevo essere il ponte che connette le persone attraverso <em style="color:var(--gold-light);">il viaggio, la cultura e le esperienze indimenticabili.</em>',
    story_p3: "Il primo viaggio di ritorno in Ghana ha cambiato tutto. Anche io, che conoscevo la lingua e la gente, sono arrivato con incertezza dopo anni lontano. Quello che abbiamo trovato andava oltre ogni immaginazione: paesaggi mozzafiato, cultura vibrante, persone calorose, cibo straordinario e avventure ad ogni angolo.",
    story_p4: '<em style="color:var(--gold-light);">"Dietro ogni paura c\'era una scoperta ancora più grande."</em>',
    stat1_label:"Regioni Esplorate", stat2_label:"Continenti Coperti", stat3_label:"Ricordi Creati", stat4_label:"Guida Appassionata",
    tl1_title:"Nato in Ghana", tl1_p:"Nana Ofori (Cyril) cresce immerso nella cultura ghanese, nella comunità e nel calore dell'Africa Occidentale.",
    tl2_title:"Quasi un Decennio in Italia", tl2_p:"Vivendo, lavorando ed esplorando l'Italia — padroneggiando la lingua, la cultura, la cucina e scoprendo gli angoli nascosti dell'Europa.",
    tl3_title:"Il Viaggio Che Ha Cambiato Tutto", tl3_p:"Cyril torna in Ghana con un amico italiano. In 3 settimane, 5 regioni, scoprono ciò che la maggior parte dei viaggiatori non vede mai.",
    tl4_title:"Nasce BB Wanderlust Tours", tl4_p:"Con la missione di connettere i continenti attraverso il viaggio autentico, BB Wanderlust lancia — il mondo ha bisogno di questo ponte.",
    tl5_title:"La Tua Avventura Inizia", tl5_p:"Ogni viaggio guidato da Cyril porta la stessa passione, energia e impegno nel mostrare alle persone il mondo per quello che è veramente.",
    book_label: "Pianifichiamo Insieme",
    book_title1: "Prenota il Tuo",
    book_title2: "Viaggio dei Sogni",
    book_intro: "Compila il modulo qui sotto e Cyril ti contatterà personalmente entro 24 ore per creare il tuo itinerario perfetto.",
    form_fname:"Nome *", form_lname:"Cognome *", form_email:"Indirizzo Email *", form_phone:"WhatsApp / Telefono",
    form_direction:"Direzione di Viaggio *", form_dir_ph:"Seleziona il tuo percorso",
    form_dir1:"Europa → Ghana / Africa", form_dir2:"Ghana / Africa → Italia / Europa", form_dir3:"In Africa", form_dir4:"In Europa", form_dir5:"Percorso Personalizzato",
    form_service:"Servizio Richiesto *", form_svc_ph:"Di cosa hai bisogno?",
    form_svc1:"Solo Voli", form_svc2:"Solo Alloggio", form_svc3:"Solo Guida Turistica", form_svc4:"Voli + Alloggio", form_svc5:"Pacchetto Completo (Voli + Alloggio + Guida)", form_svc6:"Esperienza Personalizzata",
    form_date:"Data di Viaggio Approssimativa", form_travellers:"Numero di Viaggiatori",
    form_t1:"Solo (1)", form_t2:"Coppia (2)", form_t3:"Piccolo Gruppo (3–5)", form_t4:"Gruppo (6–10)", form_t5:"Gruppo Grande (10+)",
    form_budget:"Budget (per persona)", form_budget_ph:"Budget approssimativo",
    form_b1:"Meno di €500", form_b2:"€500 – €1.500", form_b3:"€1.500 – €3.000", form_b4:"€3.000 – €5.000", form_b5:"€5.000+ (Lusso)", form_b6:"Flessibile — sorprendimi",
    form_heard:"Come ci hai trovato?", form_heard_ph:"Seleziona",
    form_h1:"Instagram", form_h2:"Amico / Referral", form_h3:"Ricerca Google", form_h4:"Altri Social Media", form_h5:"Altro",
    form_msg:"Raccontaci del tuo viaggio dei sogni *", form_msg_ph:"Descrivi la tua esperienza ideale — luoghi che vuoi vedere, cose da fare, richieste speciali o occasioni particolari...",
    form_submit:"✦ Invia la Mia Richiesta ✦",
    form_note:"📧 Le richieste vengono inviate a bbwanderlusttours@gmail.com — aspettati una risposta entro 24 ore.",
    success_title:"✦ Richiesta Ricevuta! ✦",
    success_p:"Grazie per aver contattato BB Wanderlust Tours. Cyril esaminerà personalmente la tua richiesta e ti risponderà entro 24 ore.<br><br>Nel frattempo, seguici su Instagram <strong>@bb_wanderlust_tours</strong> per ispirazione di viaggio!",
    social_label:"Segui il Viaggio",
    social_sub:"Vedi il mondo attraverso l'obiettivo di Cyril — avventure reali, momenti autentici.",
    social_ig:"Seguici su Instagram per ispirazione di viaggio, guide alle destinazioni e avventure dietro le quinte",
    social_btn:"Seguici su Instagram",
    footer_brand:"BB Wanderlust Tours — il ponte autentico tra Ghana e Italia, Africa ed Europa. Costruito sull'esperienza vissuta, guidato dalla passione.",
    footer_svc:"Servizi", footer_dest:"Destinazioni", footer_contact:"Contatti",
    footer_svc1:"Prenotazione Voli", footer_svc2:"Alloggio", footer_svc3:"Guida Turistica", footer_svc4:"Safari & Avventura", footer_svc5:"Viaggi d'Affari",
    footer_dest1:"Ghana", footer_dest2:"Italia", footer_dest3:"Kenya", footer_dest4:"Sudafrica", footer_dest5:"E Altro…",
    footer_c1:"📧 Scrivici", footer_c2:"📸 Instagram", footer_c3:"📝 Prenota Ora",
    footer_copy:"© 2025 BB Wanderlust Tours · Tutti i Diritti Riservati · Nana Ofori (Cyril)",
  }
};

let lang = 'en';

function setLang(l) {
  lang = l;
  document.documentElement.lang = l;
  document.querySelectorAll('[data-i18n]').forEach(el => {
    const key = el.getAttribute('data-i18n');
    if (T[l][key] !== undefined) el.innerHTML = T[l][key];
  });
  // Strip
  buildStrip();
  // Destinations
  document.querySelector('[data-i18n="dest1_name"]') && rebuildDests();
  // Active lang buttons
  document.querySelectorAll('.lang-btn').forEach(b => {
    b.classList.toggle('active', b.dataset.lang === l);
  });
}

function buildStrip() {
  const items = T[lang].strip;
  let html = '';
  // duplicate for seamless loop
  for (let r = 0; r < 2; r++) {
    items.forEach(item => {
      html += `<span class="strip-item">${item} <span>·</span></span>`;
    });
  }
  document.querySelectorAll('.strip-inner').forEach(el => el.innerHTML = html);
}

function filterDest(type, btn) {
  document.querySelectorAll('.dest-tab').forEach(t => t.classList.remove('active'));
  btn.classList.add('active');
  document.querySelectorAll('.dest-card').forEach(card => {
    card.style.display = (type === 'all' || card.dataset.continent === type) ? 'block' : 'none';
  });
}

function submitForm(e) {
  e.preventDefault();
  const f = e.target;
  const subject = encodeURIComponent(`BB Wanderlust Enquiry — ${f.fname.value} ${f.lname.value}`);
  const body = encodeURIComponent(
`New Travel Enquiry from BB Wanderlust Tours Website

Name: ${f.fname.value} ${f.lname.value}
Email: ${f.email.value}
Phone/WhatsApp: ${f.phone.value || 'Not provided'}
Direction: ${f.direction.value}
Service: ${f.service.value}
Travel Date: ${f.departure.value || 'Flexible'}
Travellers: ${f.travellers.value}
Budget: ${f.budget.value || 'Not specified'}

Message:
${f.message.value}

---
Sent from BB Wanderlust Tours website`
  );
  window.location.href = `mailto:bbwanderlusttours@gmail.com?subject=${subject}&body=${body}`;
  document.getElementById('bookingForm').style.display = 'none';
  const s = document.getElementById('successMsg');
  s.style.display = 'block';
  s.scrollIntoView({ behavior: 'smooth', block: 'center' });
}

document.addEventListener('DOMContentLoaded', () => {
  setLang('en');
  buildStrip();

  // Scroll nav
  window.addEventListener('scroll', () => {
    document.getElementById('navbar').classList.toggle('scrolled', window.scrollY > 60);
  });

  // Particles
  const container = document.getElementById('particles');
  for (let i = 0; i < 30; i++) {
    const p = document.createElement('div');
    p.className = 'particle';
    p.style.left = Math.random() * 100 + '%';
    p.style.animationDuration = (8 + Math.random() * 14) + 's';
    p.style.animationDelay = (Math.random() * 10) + 's';
    p.style.width = p.style.height = (1 + Math.random() * 3) + 'px';
    container.appendChild(p);
  }

  // Scroll reveal
  const observer = new IntersectionObserver(entries => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        entry.target.style.opacity = '1';
        entry.target.style.transform = 'translateY(0)';
      }
    });
  }, { threshold: 0.1 });
  document.querySelectorAll('.service-card, .exp-item, .tl-item, .stat-box, .dest-card').forEach(el => {
    el.style.opacity = '0';
    el.style.transform = 'translateY(24px)';
    el.style.transition = 'opacity 0.7s ease, transform 0.7s ease';
    observer.observe(el);
  });
});
</script>

<style>
  :root {
    --gold: #C9A84C;
    --gold-light: #F0D080;
    --gold-dark: #8B6914;
    --black: #0A0A0A;
    --dark: #111111;
    --dark2: #1A1A1A;
    --dark3: #222222;
    --cream: #F5EDD8;
    --text-muted: #999;
  }
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
  html { scroll-behavior: smooth; }
  body { background: var(--black); color: var(--cream); font-family: 'Lato', sans-serif; font-weight: 300; overflow-x: hidden; }

  /* Grain */
  body::before {
    content: '';
    position: fixed; inset: 0;
    background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 200 200' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='0.04'/%3E%3C/svg%3E");
    pointer-events: none; z-index: 1000; opacity: 0.4;
  }

  /* ── NAV ── */
  nav {
    position: fixed; top: 0; left: 0; right: 0; z-index: 900;
    display: flex; align-items: center; justify-content: space-between;
    padding: 18px 60px;
    background: linear-gradient(to bottom, rgba(0,0,0,0.95), rgba(0,0,0,0));
    transition: background 0.4s;
  }
  nav.scrolled { background: rgba(10,10,10,0.97); border-bottom: 1px solid rgba(201,168,76,0.2); }
  .nav-logo img { height: 60px; }
  .nav-links { display: flex; gap: 28px; list-style: none; }
  .nav-links a { color: var(--cream); text-decoration: none; font-family: 'Cinzel', serif; font-size: 11px; letter-spacing: 2px; text-transform: uppercase; transition: color 0.3s; }
  .nav-links a:hover { color: var(--gold-light); }

  /* Language switcher */
  .lang-switcher {
    display: flex;
    align-items: center;
    gap: 4px;
    background: rgba(201,168,76,0.08);
    border: 1px solid rgba(201,168,76,0.25);
    border-radius: 2px;
    padding: 4px;
    margin-left: 8px;
  }
  .lang-btn {
    background: transparent;
    border: none;
    color: var(--text-muted);
    font-family: 'Cinzel', serif;
    font-size: 10px;
    letter-spacing: 1.5px;
    text-transform: uppercase;
    padding: 6px 12px;
    cursor: pointer;
    transition: all 0.25s;
    border-radius: 1px;
  }
  .lang-btn.active {
    background: var(--gold);
    color: var(--black);
    font-weight: 700;
  }
  .lang-btn:not(.active):hover { color: var(--gold); }
  .lang-divider { width: 1px; height: 14px; background: rgba(201,168,76,0.3); }

  .nav-right { display: flex; align-items: center; gap: 16px; }
  .nav-cta {
    background: transparent; border: 1px solid var(--gold); color: var(--gold);
    font-family: 'Cinzel', serif; font-size: 10px; letter-spacing: 2px; text-transform: uppercase;
    padding: 10px 24px; cursor: pointer; transition: all 0.3s; text-decoration: none;
  }
  .nav-cta:hover { background: var(--gold); color: var(--black); }

  /* ── HERO ── */
  .hero { position: relative; height: 100vh; min-height: 700px; display: flex; align-items: center; justify-content: center; overflow: hidden; text-align: center; }
  .hero-bg { position: absolute; inset: 0; background: radial-gradient(ellipse 80% 60% at 50% 40%, rgba(201,168,76,0.08) 0%, transparent 70%), linear-gradient(180deg, #0A0A0A 0%, #111 50%, #0A0A0A 100%); }
  .particles { position: absolute; inset: 0; overflow: hidden; }
  .particle { position: absolute; width: 2px; height: 2px; background: var(--gold); border-radius: 50%; animation: float linear infinite; opacity: 0; }
  @keyframes float {
    0% { transform: translateY(100vh) translateX(0); opacity: 0; }
    10% { opacity: 1; } 90% { opacity: 0.6; }
    100% { transform: translateY(-10vh) translateX(40px); opacity: 0; }
  }
  .hero::before { content:''; position:absolute; top:50%;left:50%;transform:translate(-50%,-50%); width:700px;height:700px;border:1px solid rgba(201,168,76,0.08);border-radius:50%;animation:spin 40s linear infinite; }
  .hero::after { content:''; position:absolute; top:50%;left:50%;transform:translate(-50%,-50%); width:500px;height:500px;border:1px solid rgba(201,168,76,0.12);border-radius:50%;animation:spin 25s linear infinite reverse; }
  @keyframes spin { to { transform: translate(-50%,-50%) rotate(360deg); } }

  .hero-content { position:relative;z-index:2;max-width:900px;padding:0 40px;animation:heroReveal 1.6s ease-out forwards; }
  @keyframes heroReveal { from{opacity:0;transform:translateY(40px)} to{opacity:1;transform:translateY(0)} }

  .hero-eyebrow { font-family:'Cinzel',serif;font-size:11px;letter-spacing:5px;color:var(--gold);text-transform:uppercase;margin-bottom:28px;opacity:0;animation:fadeUp 1s ease 0.3s forwards; }
  .hero-logo { width:160px;margin:0 auto 32px;display:block;filter:drop-shadow(0 0 30px rgba(201,168,76,0.5));opacity:0;animation:fadeUp 1s ease 0.5s forwards; }
  .hero-title { font-family:'Cormorant Garamond',serif;font-size:clamp(46px,8vw,96px);font-weight:300;line-height:0.95;letter-spacing:-1px;margin-bottom:24px;opacity:0;animation:fadeUp 1s ease 0.7s forwards; }
  .hero-title em { font-style:italic;color:var(--gold-light);display:block; }
  .hero-sub { font-family:'Cormorant Garamond',serif;font-size:clamp(15px,2vw,21px);font-weight:300;font-style:italic;color:rgba(245,237,216,0.7);margin-bottom:48px;opacity:0;animation:fadeUp 1s ease 0.9s forwards; }
  .hero-divider { display:flex;align-items:center;gap:20px;justify-content:center;margin-bottom:48px;opacity:0;animation:fadeUp 1s ease 1s forwards; }
  .hero-divider span { color:var(--gold);font-size:18px; }
  .hero-divider::before,.hero-divider::after { content:'';flex:1;max-width:120px;height:1px;background:linear-gradient(to right,transparent,var(--gold),transparent); }
  .hero-buttons { display:flex;gap:20px;justify-content:center;flex-wrap:wrap;opacity:0;animation:fadeUp 1s ease 1.1s forwards; }
  .hero-scroll { position:absolute;bottom:40px;left:50%;transform:translateX(-50%);display:flex;flex-direction:column;align-items:center;gap:8px;color:rgba(201,168,76,0.6);font-family:'Cinzel',serif;font-size:9px;letter-spacing:3px;text-transform:uppercase;animation:bounce 2s ease-in-out infinite;z-index:2; }
  .hero-scroll::after { content:'';width:1px;height:50px;background:linear-gradient(to bottom,var(--gold),transparent); }
  @keyframes bounce { 0%,100%{transform:translateX(-50%) translateY(0)} 50%{transform:translateX(-50%) translateY(8px)} }
  @keyframes fadeUp { from{opacity:0;transform:translateY(20px)} to{opacity:1;transform:translateY(0)} }

  /* Buttons */
  .btn-primary { background:linear-gradient(135deg,var(--gold-dark),var(--gold),var(--gold-light));color:var(--black);border:none;font-family:'Cinzel',serif;font-size:11px;letter-spacing:2.5px;text-transform:uppercase;padding:16px 40px;cursor:pointer;transition:all 0.3s;text-decoration:none;display:inline-block;font-weight:600; }
  .btn-primary:hover { transform:translateY(-2px);box-shadow:0 12px 40px rgba(201,168,76,0.4); }
  .btn-outline { background:transparent;border:1px solid rgba(201,168,76,0.6);color:var(--cream);font-family:'Cinzel',serif;font-size:11px;letter-spacing:2.5px;text-transform:uppercase;padding:16px 40px;cursor:pointer;transition:all 0.3s;text-decoration:none;display:inline-block; }
  .btn-outline:hover { border-color:var(--gold);color:var(--gold);transform:translateY(-2px); }

  /* ── STRIP ── */
  .gold-strip { background:linear-gradient(90deg,var(--gold-dark),var(--gold),var(--gold-light),var(--gold),var(--gold-dark));padding:18px 0;overflow:hidden;white-space:nowrap; }
  .strip-inner { display:inline-flex;animation:marquee 22s linear infinite; }
  .strip-item { font-family:'Cinzel',serif;font-size:11px;letter-spacing:3px;color:var(--black);text-transform:uppercase;padding:0 40px; }
  .strip-item span { margin:0 10px;opacity:0.4; }
  @keyframes marquee { from{transform:translateX(0)} to{transform:translateX(-50%)} }

  /* ── SECTIONS ── */
  section { position:relative; }
  .section-inner { max-width:1200px;margin:0 auto;padding:120px 60px; }
  .section-label { font-family:'Cinzel',serif;font-size:10px;letter-spacing:5px;color:var(--gold);text-transform:uppercase;margin-bottom:20px;display:flex;align-items:center;gap:16px; }
  .section-label::before { content:'';width:40px;height:1px;background:var(--gold); }
  .section-title { font-family:'Cormorant Garamond',serif;font-size:clamp(34px,5vw,62px);font-weight:300;line-height:1.1;margin-bottom:24px; }
  .section-title em { font-style:italic;color:var(--gold-light); }

  /* ── ABOUT ── */
  .about-section { background:var(--dark); }
  .about-grid { display:grid;grid-template-columns:1fr 1fr;gap:80px;align-items:center; }
  .about-img-frame { position:relative;aspect-ratio:3/4;max-width:420px; }
  .about-img-frame::before { content:'';position:absolute;top:-16px;left:-16px;right:16px;bottom:16px;border:1px solid rgba(201,168,76,0.3);z-index:0; }
  .about-map-visual { width:100%;height:100%;background:var(--dark2);display:flex;align-items:center;justify-content:center;overflow:hidden; }
  .about-logo-large { width:280px;filter:drop-shadow(0 0 60px rgba(201,168,76,0.6));position:relative;z-index:2; }
  .about-badge { position:absolute;bottom:-24px;right:-24px;width:120px;height:120px;background:var(--gold);border-radius:50%;display:flex;flex-direction:column;align-items:center;justify-content:center;z-index:3;box-shadow:0 0 40px rgba(201,168,76,0.4); }
  .about-badge strong { font-family:'Cormorant Garamond',serif;font-size:32px;color:var(--black);line-height:1; }
  .about-badge span { font-family:'Cinzel',serif;font-size:8px;color:var(--black);letter-spacing:1.5px;text-transform:uppercase;text-align:center;line-height:1.3; }
  .about-text p { font-size:16px;line-height:1.9;color:rgba(245,237,216,0.75);margin-bottom:20px; }
  .about-text p strong { color:var(--gold-light);font-weight:400; }
  .about-quote { border-left:2px solid var(--gold);padding-left:24px;margin:36px 0;font-family:'Cormorant Garamond',serif;font-size:22px;font-style:italic;color:var(--cream);line-height:1.5; }

  /* ── SERVICES ── */
  .services-section { background:var(--black); }
  .services-grid { display:grid;grid-template-columns:repeat(3,1fr);gap:2px;margin-top:60px; }
  .service-card { background:var(--dark2);padding:50px 36px;position:relative;overflow:hidden;transition:background 0.4s; }
  .service-card::before { content:'';position:absolute;bottom:0;left:0;right:0;height:2px;background:linear-gradient(90deg,transparent,var(--gold),transparent);transform:scaleX(0);transition:transform 0.4s; }
  .service-card:hover::before { transform:scaleX(1); }
  .service-card:hover { background:var(--dark3); }
  .service-icon { font-size:36px;margin-bottom:20px;display:block; }
  .service-card h3 { font-family:'Cinzel',serif;font-size:13px;letter-spacing:2px;color:var(--gold-light);margin-bottom:14px;text-transform:uppercase; }
  .service-card p { font-size:14px;line-height:1.8;color:rgba(245,237,216,0.65); }
  .service-number { position:absolute;top:30px;right:30px;font-family:'Cormorant Garamond',serif;font-size:72px;color:rgba(201,168,76,0.06);line-height:1;font-weight:300; }

  /* ── DESTINATIONS ── */
  .destinations-section { background:var(--dark); }
  .dest-tabs { display:flex;margin:40px 0;border-bottom:1px solid rgba(201,168,76,0.2); }
  .dest-tab { font-family:'Cinzel',serif;font-size:11px;letter-spacing:2px;text-transform:uppercase;padding:14px 36px;cursor:pointer;color:var(--text-muted);border:none;border-bottom:2px solid transparent;background:none;transition:all 0.3s; }
  .dest-tab.active,.dest-tab:hover { color:var(--gold);border-bottom-color:var(--gold); }
  .dest-grid { display:grid;grid-template-columns:repeat(3,1fr);gap:20px; }
  .dest-card { position:relative;aspect-ratio:4/5;overflow:hidden;cursor:pointer; }
  .dest-card-bg { width:100%;height:100%;background-size:cover;background-position:center;transition:transform 0.6s ease; }
  .dest-card:hover .dest-card-bg { transform:scale(1.06); }
  .dest-card::after { content:'';position:absolute;inset:0;background:linear-gradient(to top,rgba(0,0,0,0.85) 0%,rgba(0,0,0,0.2) 60%,transparent 100%);pointer-events:none; }
  .dest-info { position:absolute;bottom:0;left:0;right:0;padding:28px 24px;z-index:2; }
  .dest-flag { font-size:28px;margin-bottom:6px; }
  .dest-name { font-family:'Cormorant Garamond',serif;font-size:28px;font-weight:400;color:white;line-height:1.1; }
  .dest-sub { font-family:'Cinzel',serif;font-size:9px;letter-spacing:2.5px;color:var(--gold-light);text-transform:uppercase;margin-top:4px; }
  .dest-ghana { background:linear-gradient(160deg,#1a4a2e,#2d7a4a,#8B6914,#c9a84c); }
  .dest-italy { background:linear-gradient(160deg,#1a2a4a,#2a4a8a,#c8102e,#009246); }
  .dest-safari { background:linear-gradient(160deg,#4a2a0a,#8B6914,#c9a84c,#e8d08c); }
  .dest-rome { background:linear-gradient(160deg,#2a1a0a,#8B4513,#DAA520,#FFF8DC); }
  .dest-cape { background:linear-gradient(160deg,#0a1a2a,#1a3a5a,#2a6a8a,#4a8aaa); }
  .dest-amalfi { background:linear-gradient(160deg,#0a3a1a,#1a8a4a,#2aaaaa,#2a6aaa); }

  /* ── EXPERIENCES ── */
  .experiences-section { background:var(--black); }
  .exp-list { margin-top:60px; }
  .exp-item { display:grid;grid-template-columns:80px 1fr auto;align-items:center;gap:36px;padding:32px 0;border-bottom:1px solid rgba(201,168,76,0.1);transition:all 0.3s; }
  .exp-item:first-child { border-top:1px solid rgba(201,168,76,0.1); }
  .exp-item:hover { padding-left:20px; }
  .exp-num { font-family:'Cormorant Garamond',serif;font-size:48px;font-weight:300;color:rgba(201,168,76,0.25);line-height:1; }
  .exp-content h3 { font-family:'Cormorant Garamond',serif;font-size:26px;font-weight:400;margin-bottom:6px;color:var(--cream);transition:color 0.3s; }
  .exp-item:hover .exp-content h3 { color:var(--gold-light); }
  .exp-content p { font-size:14px;color:rgba(245,237,216,0.55);line-height:1.6; }
  .exp-emoji { font-size:32px; }

  /* ── STORY ── */
  .story-section { background:var(--dark);overflow:hidden; }
  .story-section::before { content:'';position:absolute;inset:0;background:radial-gradient(ellipse 60% 80% at 80% 50%,rgba(201,168,76,0.05) 0%,transparent 70%);pointer-events:none; }
  .story-grid { display:grid;grid-template-columns:1fr 1fr;gap:100px;align-items:start; }
  .story-text p { font-size:16px;line-height:2;color:rgba(245,237,216,0.7);margin-bottom:24px; }
  .story-stats { display:grid;grid-template-columns:1fr 1fr;gap:28px;margin-top:48px; }
  .stat-box { border:1px solid rgba(201,168,76,0.2);padding:28px 24px;text-align:center;transition:border-color 0.3s; }
  .stat-box:hover { border-color:var(--gold); }
  .stat-num { font-family:'Cormorant Garamond',serif;font-size:52px;font-weight:300;color:var(--gold-light);line-height:1;display:block; }
  .stat-label { font-family:'Cinzel',serif;font-size:9px;letter-spacing:2px;color:var(--text-muted);text-transform:uppercase;margin-top:8px; }
  .story-timeline { padding-top:12px; }
  .tl-item { display:flex;gap:24px;margin-bottom:40px;position:relative; }
  .tl-item::before { content:'';position:absolute;left:20px;top:44px;bottom:-40px;width:1px;background:linear-gradient(to bottom,var(--gold),transparent); }
  .tl-item:last-child::before { display:none; }
  .tl-dot { width:42px;height:42px;border:1px solid var(--gold);border-radius:50%;display:flex;align-items:center;justify-content:center;flex-shrink:0;font-size:18px; }
  .tl-content h4 { font-family:'Cinzel',serif;font-size:12px;letter-spacing:1.5px;color:var(--gold-light);margin-bottom:6px;text-transform:uppercase; }
  .tl-content p { font-size:14px;color:rgba(245,237,216,0.65);line-height:1.7; }

  /* ── BOOKING ── */
  .booking-section { background:var(--black); }
  .booking-wrap { max-width:860px;margin:60px auto 0; }
  .form-grid { display:grid;grid-template-columns:1fr 1fr;gap:24px; }
  .form-group { display:flex;flex-direction:column;gap:8px; }
  .form-group.full { grid-column:1/-1; }
  .form-group label { font-family:'Cinzel',serif;font-size:9px;letter-spacing:2.5px;color:var(--gold);text-transform:uppercase; }
  .form-group input,.form-group select,.form-group textarea { background:var(--dark2);border:1px solid rgba(201,168,76,0.2);color:var(--cream);padding:14px 18px;font-family:'Lato',sans-serif;font-size:14px;font-weight:300;outline:none;transition:border-color 0.3s;-webkit-appearance:none; }
  .form-group input:focus,.form-group select:focus,.form-group textarea:focus { border-color:var(--gold); }
  .form-group select option { background:var(--dark2); }
  .form-group textarea { resize:vertical;min-height:120px; }
  .form-submit { margin-top:32px;text-align:center; }
  .form-submit button { background:linear-gradient(135deg,var(--gold-dark),var(--gold),var(--gold-light));color:var(--black);border:none;font-family:'Cinzel',serif;font-size:12px;letter-spacing:3px;text-transform:uppercase;padding:18px 60px;cursor:pointer;font-weight:700;transition:all 0.3s; }
  .form-submit button:hover { transform:translateY(-3px);box-shadow:0 16px 48px rgba(201,168,76,0.35); }
  .form-note { margin-top:16px;font-size:12px;color:var(--text-muted);font-style:italic; }
  .success-message { display:none;background:rgba(201,168,76,0.1);border:1px solid var(--gold);padding:28px;text-align:center;margin-top:28px; }
  .success-message h4 { font-family:'Cormorant Garamond',serif;font-size:26px;color:var(--gold-light);margin-bottom:10px; }
  .success-message p { font-size:14px;color:rgba(245,237,216,0.7); }

  /* ── SOCIAL ── */
  .social-section { background:var(--dark);text-align:center; }
  .social-section .section-inner { padding-top:80px;padding-bottom:80px; }
  .ig-handle { font-family:'Cormorant Garamond',serif;font-size:42px;font-weight:300;font-style:italic;color:var(--gold-light);margin-top:20px;display:block;text-decoration:none;transition:color 0.3s; }
  .ig-handle:hover { color:var(--gold); }
  .ig-sub { font-size:14px;color:var(--text-muted);margin-top:10px; }
  .ig-icon { font-size:48px;display:block;margin-bottom:16px; }

  /* ── FOOTER ── */
  footer { background:var(--black);border-top:1px solid rgba(201,168,76,0.15);padding:60px;display:grid;grid-template-columns:2fr 1fr 1fr 1fr;gap:60px;align-items:start; }
  .footer-brand img { height:70px;margin-bottom:16px;filter:drop-shadow(0 0 10px rgba(201,168,76,0.3)); }
  .footer-brand p { font-size:13px;color:var(--text-muted);line-height:1.8;max-width:280px; }
  .footer-col h4 { font-family:'Cinzel',serif;font-size:10px;letter-spacing:2.5px;color:var(--gold);text-transform:uppercase;margin-bottom:20px; }
  .footer-col ul { list-style:none; }
  .footer-col ul li { margin-bottom:10px; }
  .footer-col ul li a { color:var(--text-muted);text-decoration:none;font-size:13px;transition:color 0.3s; }
  .footer-col ul li a:hover { color:var(--gold-light); }
  .footer-bottom { background:var(--black);border-top:1px solid rgba(255,255,255,0.05);padding:24px 60px;display:flex;justify-content:space-between;align-items:center; }
  .footer-bottom p { font-size:12px;color:rgba(255,255,255,0.2); }
  .footer-bottom a { color:var(--gold);text-decoration:none;font-size:12px; }

  /* ── RESPONSIVE ── */
  @media (max-width:900px) {
    nav { padding:16px 20px; }
    .nav-links { display:none; }
    .section-inner { padding:80px 24px; }
    .about-grid,.story-grid { grid-template-columns:1fr;gap:40px; }
    .services-grid { grid-template-columns:1fr; }
    .dest-grid { grid-template-columns:1fr 1fr; }
    .form-grid { grid-template-columns:1fr; }
    footer { grid-template-columns:1fr;gap:36px;padding:40px 24px; }
    .footer-bottom { padding:20px 24px;flex-direction:column;gap:8px;text-align:center; }
    .hero-logo { width:110px; }
    .about-img-frame { max-width:100%; }
    .lang-btn { padding:5px 9px;font-size:9px; }
  }
  @media (max-width:600px) {
    .dest-grid { grid-template-columns:1fr; }
    .hero-buttons { flex-direction:column;align-items:center; }
    .story-stats { grid-template-columns:1fr 1fr; }
  }
</style>
</head>
<body>

<!-- ── NAV ── -->
<nav id="navbar">
  <div class="nav-logo">
    <img src="logo.png" alt="BB Wanderlust Tours" onerror="this.style.display='none'">
  </div>
  <ul class="nav-links">
    <li><a href="#about" data-i18n="nav_about">About</a></li>
    <li><a href="#services" data-i18n="nav_services">Services</a></li>
    <li><a href="#destinations" data-i18n="nav_destinations">Destinations</a></li>
    <li><a href="#story" data-i18n="nav_story">Our Story</a></li>
    <li><a href="#book" data-i18n="nav_book">Book</a></li>
  </ul>
  <div class="nav-right">
    <div class="lang-switcher">
      <button class="lang-btn active" data-lang="en" onclick="setLang('en')">EN</button>
      <div class="lang-divider"></div>
      <button class="lang-btn" data-lang="it" onclick="setLang('it')">IT</button>
    </div>
    <a href="#book" class="nav-cta" data-i18n="nav_cta">Plan My Trip</a>
  </div>
</nav>

<!-- ── HERO ── -->
<section class="hero" id="home">
  <div class="hero-bg"></div>
  <div class="particles" id="particles"></div>
  <div class="hero-content">
    <div class="hero-eyebrow" data-i18n="hero_eyebrow">Africa · Europe · Beyond</div>
    <img src="logo.png" alt="BB Wanderlust Tours" class="hero-logo" onerror="this.style.display='none'">
    <h1 class="hero-title">
      <span data-i18n="hero_title1">Where Two</span><br>
      <em data-i18n="hero_title2">Continents Unite</em>
    </h1>
    <p class="hero-sub" data-i18n="hero_sub">Your authentic bridge between Ghana &amp; Italy — curated journeys, real connections, lifelong memories.</p>
    <div class="hero-divider"><span>✦</span></div>
    <div class="hero-buttons">
      <a href="#book" class="btn-primary" data-i18n="hero_btn1">Start Your Journey</a>
      <a href="#story" class="btn-outline" data-i18n="hero_btn2">Our Story</a>
    </div>
  </div>
  <div class="hero-scroll" data-i18n="hero_scroll">Scroll</div>
</section>

<!-- ── STRIP ── -->
<div class="gold-strip">
  <div class="strip-inner"></div>
</div>

<!-- ── ABOUT ── -->
<section class="about-section" id="about">
  <div class="section-inner">
    <div class="about-grid">
      <div class="about-visual">
        <div class="about-img-frame">
          <div class="about-map-visual">
            <img src="logo.png" alt="BB Wanderlust Tours" class="about-logo-large" onerror="this.style.display='none'">
          </div>
          <div class="about-badge">
            <strong data-i18n="about_badge_top">2</strong>
            <span data-i18n="about_badge_bot">Continents<br>One Guide</span>
          </div>
        </div>
      </div>
      <div class="about-text">
        <div class="section-label" data-i18n="about_label">About Us</div>
        <h2 class="section-title">
          <span data-i18n="about_title1">Meet Your</span> <em data-i18n="about_title2">Bridge</em><br>
          <span data-i18n="about_title3">Between Worlds</span>
        </h2>
        <blockquote class="about-quote" data-i18n="about_quote">"My European friends wanted Africa. My African friends wanted Europe. I realized I could be the bridge."</blockquote>
        <p data-i18n="about_p1">My name is <strong>Nana Ofori (Cyril)</strong>, founder of BB Wanderlust Tours...</p>
        <p data-i18n="about_p2">What sets BB Wanderlust apart is lived experience...</p>
        <p data-i18n="about_p3">In just three weeks, we explored 5 regions of Ghana...</p>
        <a href="#book" class="btn-primary" style="margin-top:16px;" data-i18n="about_btn">Book a Consultation</a>
      </div>
    </div>
  </div>
</section>

<!-- ── SERVICES ── -->
<section class="services-section" id="services">
  <div class="section-inner">
    <div class="section-label" data-i18n="svc_label">What We Offer</div>
    <h2 class="section-title"><span data-i18n="svc_title1">Our</span> <em data-i18n="svc_title2">Services</em></h2>
    <p style="font-size:16px;color:rgba(245,237,216,0.6);max-width:560px;line-height:1.8;" data-i18n="svc_sub">End-to-end travel support...</p>
    <div class="services-grid">
      <div class="service-card"><span class="service-number">01</span><span class="service-icon">✈️</span><h3 data-i18n="svc1_title">Flight Booking</h3><p data-i18n="svc1_p">We find the most affordable...</p></div>
      <div class="service-card"><span class="service-number">02</span><span class="service-icon">🏨</span><h3 data-i18n="svc2_title">Accommodation</h3><p data-i18n="svc2_p">From boutique guesthouses...</p></div>
      <div class="service-card"><span class="service-number">03</span><span class="service-icon">🗺️</span><h3 data-i18n="svc3_title">Private Tour Guide</h3><p data-i18n="svc3_p">With Cyril as your guide...</p></div>
      <div class="service-card"><span class="service-number">04</span><span class="service-icon">🦁</span><h3 data-i18n="svc4_title">Safari & Adventures</h3><p data-i18n="svc4_p">Wildlife safaris, Lamborghini drives...</p></div>
      <div class="service-card"><span class="service-number">05</span><span class="service-icon">💼</span><h3 data-i18n="svc5_title">Business Travel</h3><p data-i18n="svc5_p">Connecting entrepreneurs...</p></div>
      <div class="service-card"><span class="service-number">06</span><span class="service-icon">🍝</span><h3 data-i18n="svc6_title">Cultural Immersion</h3><p data-i18n="svc6_p">Food tours, local markets...</p></div>
    </div>
  </div>
</section>

<!-- ── DESTINATIONS ── -->
<section class="destinations-section" id="destinations">
  <div class="section-inner">
    <div class="section-label" data-i18n="dest_label">Destinations</div>
    <h2 class="section-title"><span data-i18n="dest_title1">Two Continents,</span><br><em data-i18n="dest_title2">Infinite Possibilities</em></h2>
    <div class="dest-tabs">
      <button class="dest-tab active" onclick="filterDest('all',this)" data-i18n="dest_all">All</button>
      <button class="dest-tab" onclick="filterDest('africa',this)" data-i18n="dest_africa">Africa 🌍</button>
      <button class="dest-tab" onclick="filterDest('europe',this)" data-i18n="dest_europe">Europe 🏛️</button>
    </div>
    <div class="dest-grid">
      <div class="dest-card" data-continent="africa"><div class="dest-card-bg dest-ghana"></div><div class="dest-info"><div class="dest-flag">🇬🇭</div><div class="dest-name" data-i18n="dest1_name">Accra, Ghana</div><div class="dest-sub" data-i18n="dest1_sub">The Heart of West Africa</div></div></div>
      <div class="dest-card" data-continent="europe"><div class="dest-card-bg dest-italy"></div><div class="dest-info"><div class="dest-flag">🇮🇹</div><div class="dest-name" data-i18n="dest2_name">Rome, Italy</div><div class="dest-sub" data-i18n="dest2_sub">The Eternal City</div></div></div>
      <div class="dest-card" data-continent="africa"><div class="dest-card-bg dest-safari"></div><div class="dest-info"><div class="dest-flag">🦁</div><div class="dest-name" data-i18n="dest3_name">Safari, Kenya</div><div class="dest-sub" data-i18n="dest3_sub">Wild Africa Awaits</div></div></div>
      <div class="dest-card" data-continent="europe"><div class="dest-card-bg dest-amalfi"></div><div class="dest-info"><div class="dest-flag">🏖️</div><div class="dest-name" data-i18n="dest4_name">Amalfi Coast</div><div class="dest-sub" data-i18n="dest4_sub">Italy's Jewel Shore</div></div></div>
      <div class="dest-card" data-continent="africa"><div class="dest-card-bg dest-cape"></div><div class="dest-info"><div class="dest-flag">🇿🇦</div><div class="dest-name" data-i18n="dest5_name">Cape Town, SA</div><div class="dest-sub" data-i18n="dest5_sub">Where Oceans Meet</div></div></div>
      <div class="dest-card" data-continent="europe"><div class="dest-card-bg dest-rome"></div><div class="dest-info"><div class="dest-flag">🛕</div><div class="dest-name" data-i18n="dest6_name">Florence, Italy</div><div class="dest-sub" data-i18n="dest6_sub">Art, Culture & Renaissance</div></div></div>
    </div>
    <p style="text-align:center;margin-top:40px;font-size:14px;color:var(--text-muted);font-style:italic;" data-i18n="dest_note">And many more destinations...</p>
  </div>
</section>

<!-- ── EXPERIENCES ── -->
<section class="experiences-section">
  <div class="section-inner">
    <div class="section-label" data-i18n="exp_label">Experiences</div>
    <h2 class="section-title"><span data-i18n="exp_title1">Beyond the</span> <em data-i18n="exp_title2">Ordinary</em></h2>
    <div class="exp-list">
      <div class="exp-item"><div class="exp-num">01</div><div class="exp-content"><h3 data-i18n="exp1_title">Lamborghini & Supercar Drives, Ghana</h3><p data-i18n="exp1_p">Experience the thrill...</p></div><div class="exp-emoji">🏎️</div></div>
      <div class="exp-item"><div class="exp-num">02</div><div class="exp-content"><h3 data-i18n="exp2_title">Ghana Regional Road Trip — 5 Regions</h3><p data-i18n="exp2_p">Follow the route...</p></div><div class="exp-emoji">🗺️</div></div>
      <div class="exp-item"><div class="exp-num">03</div><div class="exp-content"><h3 data-i18n="exp3_title">Coastal Beach Resorts & Private Islands</h3><p data-i18n="exp3_p">From Ghana's pristine...</p></div><div class="exp-emoji">🏖️</div></div>
      <div class="exp-item"><div class="exp-num">04</div><div class="exp-content"><h3 data-i18n="exp4_title">Local Street Food & Hidden Market Tours</h3><p data-i18n="exp4_p">From kelewele...</p></div><div class="exp-emoji">🍽️</div></div>
      <div class="exp-item"><div class="exp-num">05</div><div class="exp-content"><h3 data-i18n="exp5_title">Italian Art, History & Architecture</h3><p data-i18n="exp5_p">Florence, Venice, Rome...</p></div><div class="exp-emoji">🏛️</div></div>
    </div>
  </div>
</section>

<!-- ── STORY ── -->
<section class="story-section" id="story">
  <div class="section-inner">
    <div class="section-label" data-i18n="story_label">The BB Wanderlust Story</div>
    <div class="story-grid">
      <div class="story-text">
        <h2 class="section-title" style="margin-bottom:36px;"><span data-i18n="story_title1">Born From</span> <em data-i18n="story_title2">Two Worlds</em></h2>
        <p data-i18n="story_p1">The idea for BB Wanderlust was born...</p>
        <p data-i18n="story_p2">Since my life had always been between...</p>
        <p data-i18n="story_p3">The first journey back to Ghana changed everything...</p>
        <p data-i18n="story_p4"><em style="color:var(--gold-light);">"Behind every fear was an even greater discovery."</em></p>
        <div class="story-stats">
          <div class="stat-box"><span class="stat-num">5+</span><span class="stat-label" data-i18n="stat1_label">Regions Explored</span></div>
          <div class="stat-box"><span class="stat-num">2</span><span class="stat-label" data-i18n="stat2_label">Continents Covered</span></div>
          <div class="stat-box"><span class="stat-num">∞</span><span class="stat-label" data-i18n="stat3_label">Memories Created</span></div>
          <div class="stat-box"><span class="stat-num">1</span><span class="stat-label" data-i18n="stat4_label">Passionate Guide</span></div>
        </div>
      </div>
      <div class="story-timeline">
        <div class="tl-item"><div class="tl-dot">🇬🇭</div><div class="tl-content"><h4 data-i18n="tl1_title">Born in Ghana</h4><p data-i18n="tl1_p">Nana Ofori (Cyril) grows up immersed...</p></div></div>
        <div class="tl-item"><div class="tl-dot">🇮🇹</div><div class="tl-content"><h4 data-i18n="tl2_title">Nearly a Decade in Italy</h4><p data-i18n="tl2_p">Living, working and exploring Italy...</p></div></div>
        <div class="tl-item"><div class="tl-dot">✈️</div><div class="tl-content"><h4 data-i18n="tl3_title">The Journey That Changed Everything</h4><p data-i18n="tl3_p">Cyril returns to Ghana with an Italian friend...</p></div></div>
        <div class="tl-item"><div class="tl-dot">🌟</div><div class="tl-content"><h4 data-i18n="tl4_title">BB Wanderlust Tours Is Born</h4><p data-i18n="tl4_p">With a mission to connect continents...</p></div></div>
        <div class="tl-item"><div class="tl-dot">🚀</div><div class="tl-content"><h4 data-i18n="tl5_title">Your Adventure Begins</h4><p data-i18n="tl5_p">Every journey Cyril guides carries the same passion...</p></div></div>
      </div>
    </div>
  </div>
</section>

<!-- ── BOOKING ── -->
<section class="booking-section" id="book">
  <div class="section-inner">
    <div style="text-align:center;max-width:600px;margin:0 auto 0;">
      <div class="section-label" style="justify-content:center;" data-i18n="book_label">Let's Plan Together</div>
      <h2 class="section-title" style="text-align:center;"><span data-i18n="book_title1">Book Your</span> <em data-i18n="book_title2">Dream Journey</em></h2>
      <p style="font-size:15px;color:rgba(245,237,216,0.6);line-height:1.8;" data-i18n="book_intro">Fill out the form below...</p>
    </div>
    <div class="booking-wrap">
      <form id="bookingForm" onsubmit="submitForm(event)">
        <div class="form-grid">
          <div class="form-group"><label data-i18n="form_fname">First Name *</label><input type="text" name="fname" required placeholder=""></div>
          <div class="form-group"><label data-i18n="form_lname">Last Name *</label><input type="text" name="lname" required placeholder=""></div>
          <div class="form-group"><label data-i18n="form_email">Email Address *</label><input type="email" name="email" required placeholder="you@email.com"></div>
          <div class="form-group"><label data-i18n="form_phone">WhatsApp / Phone</label><input type="tel" name="phone" placeholder="+39 / +233..."></div>
          <div class="form-group">
            <label data-i18n="form_direction">Travel Direction *</label>
            <select name="direction" required>
              <option value="" disabled selected data-i18n="form_dir_ph">Select your route</option>
              <option data-i18n="form_dir1">Europe → Ghana / Africa</option>
              <option data-i18n="form_dir2">Ghana / Africa → Italy / Europe</option>
              <option data-i18n="form_dir3">Within Africa</option>
              <option data-i18n="form_dir4">Within Europe</option>
              <option data-i18n="form_dir5">Custom Route</option>
            </select>
          </div>
          <div class="form-group">
            <label data-i18n="form_service">Service Needed *</label>
            <select name="service" required>
              <option value="" disabled selected data-i18n="form_svc_ph">What do you need?</option>
              <option data-i18n="form_svc1">Flights Only</option>
              <option data-i18n="form_svc2">Accommodation Only</option>
              <option data-i18n="form_svc3">Tour Guide Only</option>
              <option data-i18n="form_svc4">Flights + Accommodation</option>
              <option data-i18n="form_svc5">Full Package</option>
              <option data-i18n="form_svc6">Custom Experience</option>
            </select>
          </div>
          <div class="form-group"><label data-i18n="form_date">Approximate Travel Date</label><input type="date" name="departure"></div>
          <div class="form-group">
            <label data-i18n="form_travellers">Number of Travellers</label>
            <select name="travellers">
              <option data-i18n="form_t1">Solo (1)</option>
              <option data-i18n="form_t2">Couple (2)</option>
              <option data-i18n="form_t3">Small Group (3–5)</option>
              <option data-i18n="form_t4">Group (6–10)</option>
              <option data-i18n="form_t5">Large Group (10+)</option>
            </select>
          </div>
          <div class="form-group">
            <label data-i18n="form_budget">Budget Range (per person)</label>
            <select name="budget">
              <option value="" disabled selected data-i18n="form_budget_ph">Approximate budget</option>
              <option data-i18n="form_b1">Under €500 / $500</option>
              <option data-i18n="form_b2">€500 – €1,500</option>
              <option data-i18n="form_b3">€1,500 – €3,000</option>
              <option data-i18n="form_b4">€3,000 – €5,000</option>
              <option data-i18n="form_b5">€5,000+ (Luxury)</option>
              <option data-i18n="form_b6">Flexible — surprise me</option>
            </select>
          </div>
          <div class="form-group">
            <label data-i18n="form_heard">How did you find us?</label>
            <select name="heard">
              <option value="" disabled selected data-i18n="form_heard_ph">Select one</option>
              <option data-i18n="form_h1">Instagram</option>
              <option data-i18n="form_h2">Friend / Referral</option>
              <option data-i18n="form_h3">Google Search</option>
              <option data-i18n="form_h4">Other Social Media</option>
              <option data-i18n="form_h5">Other</option>
            </select>
          </div>
          <div class="form-group full">
            <label data-i18n="form_msg">Tell us about your dream trip *</label>
            <textarea name="message" required data-i18n-placeholder="form_msg_ph" placeholder="Describe your ideal experience..."></textarea>
          </div>
        </div>
        <div class="form-submit">
          <button type="submit" data-i18n="form_submit">✦ Send My Enquiry ✦</button>
          <p class="form-note" data-i18n="form_note">📧 Enquiries are sent to bbwanderlusttours@gmail.com — expect a reply within 24 hours.</p>
        </div>
      </form>
      <div class="success-message" id="successMsg">
        <h4 data-i18n="success_title">✦ Enquiry Received! ✦</h4>
        <p data-i18n="success_p">Thank you for reaching out...</p>
      </div>
    </div>
  </div>
</section>

<!-- ── SOCIAL ── -->
<section class="social-section">
  <div class="section-inner">
    <div class="section-label" style="justify-content:center;" data-i18n="social_label">Follow the Journey</div>
    <p style="font-size:18px;color:rgba(245,237,216,0.6);font-family:'Cormorant Garamond',serif;font-style:italic;" data-i18n="social_sub">See the world through Cyril's lens...</p>
    <span class="ig-icon">📸</span>
    <a href="https://www.instagram.com/bb_wanderlust_tours?igsh=dm9iemtuNXY3Z2F4" target="_blank" class="ig-handle">@bb_wanderlust_tours</a>
    <p class="ig-sub" data-i18n="social_ig">Follow us on Instagram for travel inspiration...</p>
    <a href="https://www.instagram.com/bb_wanderlust_tours?igsh=dm9iemtuNXY3Z2F4" target="_blank" class="btn-primary" style="margin-top:32px;display:inline-block;" data-i18n="social_btn">Follow on Instagram</a>
  </div>
</section>

<!-- ── FOOTER ── -->
<footer>
  <div class="footer-brand">
    <img src="logo.png" alt="BB Wanderlust Tours" onerror="this.style.display='none'">
    <p data-i18n="footer_brand">BB Wanderlust Tours — the authentic bridge between Ghana & Italy...</p>
  </div>
  <div class="footer-col">
    <h4 data-i18n="footer_svc">Services</h4>
    <ul>
      <li><a href="#services" data-i18n="footer_svc1">Flight Booking</a></li>
      <li><a href="#services" data-i18n="footer_svc2">Accommodation</a></li>
      <li><a href="#services" data-i18n="footer_svc3">Tour Guide</a></li>
      <li><a href="#services" data-i18n="footer_svc4">Safari & Adventure</a></li>
      <li><a href="#services" data-i18n="footer_svc5">Business Travel</a></li>
    </ul>
  </div>
  <div class="footer-col">
    <h4 data-i18n="footer_dest">Destinations</h4>
    <ul>
      <li><a href="#destinations" data-i18n="footer_dest1">Ghana</a></li>
      <li><a href="#destinations" data-i18n="footer_dest2">Italy</a></li>
      <li><a href="#destinations" data-i18n="footer_dest3">Kenya</a></li>
      <li><a href="#destinations" data-i18n="footer_dest4">South Africa</a></li>
      <li><a href="#destinations" data-i18n="footer_dest5">And More…</a></li>
    </ul>
  </div>
  <div class="footer-col">
    <h4 data-i18n="footer_contact">Contact</h4>
    <ul>
      <li><a href="mailto:bbwanderlusttours@gmail.com" data-i18n="footer_c1">📧 Email Us</a></li>
      <li><a href="https://www.instagram.com/bb_wanderlust_tours" target="_blank" data-i18n="footer_c2">📸 Instagram</a></li>
      <li><a href="#book" data-i18n="footer_c3">📝 Book Now</a></li>
    </ul>
  </div>
</footer>
<div class="footer-bottom">
  <p data-i18n="footer_copy">© 2025 BB Wanderlust Tours · All Rights Reserved · Nana Ofori (Cyril)</p>
  <a href="mailto:bbwanderlusttours@gmail.com">bbwanderlusttours@gmail.com</a>
</div>

</body>
</html>
