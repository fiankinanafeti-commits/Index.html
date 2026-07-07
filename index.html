let currentNetwork = "facebook";

// Gestion des clics sur les boutons de réseaux sociaux
document.querySelectorAll('.network-btn').forEach(button => {
    button.addEventListener('click', function() {
        document.querySelectorAll('.network-btn').forEach(b => b.classList.remove('active'));
        this.classList.add('active');
        
        currentNetwork = this.getAttribute('data-net');
        updatePreviewStyle();
    });
});

// Écouteur sur le bouton de génération
document.getElementById('btn-generate').addEventListener('click', generateContentByAI);

function updatePreviewStyle() {
    const avatar = document.getElementById('networkAvatar');
    const name = document.getElementById('previewAccountName');
    
    if (currentNetwork === "facebook") { 
        avatar.style.backgroundColor = "var(--facebook)"; 
        name.innerText = "Ma Page Facebook Business"; 
    }
    else if (currentNetwork === "instagram") { 
        avatar.style.backgroundColor = "var(--instagram)"; 
        name.innerText = "@boutique_officielle_mg"; 
    }
    else if (currentNetwork === "tiktok") { 
        avatar.style.backgroundColor = "#000000"; 
        name.innerText = "@tiktok_vendeur_tana"; 
    }
}

function generateContentByAI() {
    const prompt = document.getElementById('prompt').value;
    const lang = document.getElementById('language').value;
    const previewText = document.getElementById('previewText');
    const scheduleList = document.getElementById('scheduleList');

    if (!prompt) { 
        alert("Indiquez votre idée d'abord !"); 
        return; 
    }

    let resultText = "";

    // Moteur d'IA localisé (Malagasy / Français)
    if (lang === "mg") {
        if (currentNetwork === "facebook") {
            resultText = `✨ SOUVENIR SY PÉPITE VAOVAO BE ! ✨\n\n🔎 ${prompt}\n\n👉 Entana tsara kalitao, sady mirary vidy be! \n📥 Andrasana eny amin'ny MP (Message Privé) izay liana.\n🚚 Misy livraison manerana an'i Tana sy ny faritra! \n\n#VitaMalagasy #FriperieTana #CommerceMG`;
        } else if (currentNetwork === "instagram") {
            resultText = `📸 Trendy be sady Class ! \n\n${prompt} ❤️ Zay te ho tsara style foana.\n\nCommande en MP ihany ry namana! 👇\n.\n#ModeMalagasy #InstaTana #StyleMG`;
        } else {
            resultText = `🎵 POV: Rehefa nahita an'ity entana ity ianao teo Analakely filamatra be! 🤫\n\n${prompt} \n\nKitiho ny rohy amin'ny bio raha hanafatra malady! 🚀\n\n#PourToi #MalagasyTikTok #FypMG`;
        }
    } else {
        if (currentNetwork === "facebook") {
            resultText = `🔥 DISPONIBLE IMMÉDIATEMENT ! 🔥\n\n📢 Nouvel arrivage : ${prompt}\n\nStock limité ! Pour commander ou demander les tarifs, contactez-nous directement en Message Privé (MP). 📥\n\n#ShoppingMadagascar #BonsPlansTana`;
        } else {
            resultText = `✨ Zoom sur notre sélection ✨\n\n${prompt} \n\nLien direct de commande disponible dans notre biographie. 🔗`;
        }
    }

    previewText.innerText = resultText;
    scheduleList.innerHTML = `<div class="schedule-item"><strong>[File d'attente]</strong> Prêt pour publication automatique (Heure de Madagascar).</div>`;
}

// Initialisation des icônes au chargement
window.onload = function() { 
    lucide.createIcons(); 
};
