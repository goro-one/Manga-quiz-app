// --- 1. CONFIGURATION DES ROLES ---
const CREW_ROLES = ["CAPITAINE", "BRAS DROIT", "NAVIGATEUR", "CUISINIER", "MÉDECIN", "SNIPER", "CHARPENTIER", "MUSICIEN"];

// --- 2. LISTE IMAGES (ONE PIECE) ---
const OP_POOL = [
    { name: "Luffy", img: "luffy.jpg" }, 
    { name: "Zoro", img: "zoro.jpg" },
    { name: "Sanji", img: "sanji.jpg" },
    { name: "Nami", img: "nami.jpg" },
    { name: "Usopp", img: "usopp.jpg" },
    { name: "Chopper", img: "chopper.jpg" },
    { name: "Robin", img: "robin.jpg" },
    { name: "Franky", img: "franky.jpg" },
    { name: "Brook", img: "brook.jpg" },
    { name: "Jinbe", img: "jinbe.jpg" },
    { name: "Law", img: "law.jpg" },
    { name: "Kid", img: "kid.jpg" },
    { name: "Kaido", img: "kaido.jpg" },
    { name: "Big Mom", img: "bigmom.jpg" },
    { name: "Shanks", img: "shanks.jpg" },
    { name: "Blackbeard", img: "blackbeard.jpg" },
    { name: "Whitebeard", img: "whitebeard.jpg" },
    { name: "Mihawk", img: "mihawk.jpg" },
    { name: "Doflamingo", img: "doflamingo.jpg" },
    { name: "Crocodile", img: "crocodile.jpg" },
    { name: "Hancock", img: "hancock.jpg" },
    { name: "Buggy", img: "buggy.jpg" },
    { name: "Marco", img: "marco.jpg" },
    { name: "Ace", img: "ace.jpg" },
    { name: "Sabo", img: "sabo.jpg" },
    { name: "Yamato", img: "yamato.jpg" }
];

// --- 3. LISTE EMOJIS ---
const EMOJI_POOL = [
    { emojis: "👒☠️🍖", answers: ["luffy"] },
    { emojis: "⚔️🟢🍶", answers: ["zoro"] },
    { emojis: "🍊💰🌩️", answers: ["nami"] },
    { emojis: "🤥🎯🔨", answers: ["usopp"] },
    { emojis: "🚬👨‍🍳🔥", answers: ["sanji"] },
    { emojis: "🦌🩺🍬", answers: ["chopper"] },
    { emojis: "🖐️🌸📚", answers: ["robin"] },
    { emojis: "🤖🥤🔧", answers: ["franky"] },
    { emojis: "💀🎻🎼", answers: ["brook"] },
    { emojis: "🦈🥋🌊", answers: ["jinbe"] },
    { emojis: "🔥🍩🤠", answers: ["ace"] },
    { emojis: "🐊⌛🚬", answers: ["crocodile"] },
    { emojis: "🦩🕶️🧶", answers: ["doflamingo"] },
    { emojis: "🐲🌩️👹", answers: ["kaido"] },
    { emojis: "🎂🌩️👵", answers: ["big mom"] }
];


// --- 4. LISTE DES QUIZ (LE MENU) ---
// C'est ICI que tu ajoutes des catégories !
const QUIZ_CONFIG = [
    {
        id: "op_crew",
        type: "duel",  // ou "emoji"
        title: "COMPOSE TON ÉQUIPAGE",
        icon: "🏴‍☠️",
        bg: "linear-gradient(135deg, #006994 0%, #003366 100%)",
        pool: OP_POOL,
        roles: CREW_ROLES
    },
    {
        id: "op_emoji",
        type: "emoji",
        title: "DEVINE LE PERSO",
        icon: "🧩",
        bg: "linear-gradient(135deg, #4b6cb7 0%, #182848 100%)",
        pool: EMOJI_POOL,
        questionCount: 5
    }
    // <-- Tu ajoutes ton nouveau quiz ici !
];
