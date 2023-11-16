<script>
	import Hero from "../component/Hero.svelte";
    import TitleH2 from "../component/TitleH2.svelte";
	import Name from "../component/Name.svelte";
</script>

<Hero title="Mentions légales"/>
<section>
    <p>Conformément aux dispositions de la loi n° 2004-575 du 21 juin 2004 pour la confiance en l'économie numérique, il est précisé aux utilisateurs du Site l'identité des différents intervenants dans le cadre de sa réalisation et de son suivi.</p>
    <TitleH2>Editeur du site</TitleH2>
    <Name name="Heloïse PINGITORE" adresse="1 rue Jacques Ellul, 33800 Bordeaux" mail="heloise.pingitore@mmibordeaux.com" />
    <TitleH2>Hébergement</TitleH2>
    <p>Netlifly.com<br> San Francisco, California</p>
    <TitleH2>Conception et Réalisation</TitleH2>
    <Name name="Phuc NGUYEN" adresse="1 rue Jacques Ellul, 33800 Bordeaux" mail="dang-thien-phuc.nguyen@mmibordeaux.com" />
    <Name name="Eve TISSOT" adresse="1 rue Jacques Ellul, 33800 Bordeaux" mail="eve.tissot@mmibordeaux.com" />
    <Name name="Naëlle LEMENNICIER" adresse="1 rue Jacques Ellul, 33800 Bordeaux" mail="naelle.lemennicier@mmibordeaux.com" />
    <Name name="Dina RAKOTONARIVO" adresse="1 rue Jacques Ellul, 33800 Bordeaux" mail="dina.rakotonarivo@mmibordeaux.com" />
    <Name name="Alexis JUHEL" adresse="1 rue Jacques Ellul, 33800 Bordeaux" mail="alexis.juhel@mmibordeaux.com" />
    <Name name="Léa LAFAYE" adresse="1 rue Jacques Ellul, 33800 Bordeaux" mail="lea.lafaye@mmibordeaux.com" />
    <Name name="Astrid CHAPRON" adresse="1 rue Jacques Ellul, 33800 Bordeaux" mail="astrid.chapron@mmibordeaux.com" />
    <Name name="Heloïse PINGITORE" adresse="1 rue Jacques Ellul, 33800 Bordeaux" mail="heloise.pingitore@mmibordeaux.com" />
    <Name name="Chloé FAYE" adresse="1 rue Jacques Ellul, 33800 Bordeaux" mail="chloe.faye@mmibordeaux.com" />
    <Name name="Perrine JOLY" adresse="1 rue Jacques Ellul, 33800 Bordeaux" mail="perrine.joly@mmibordeaux.com" />
    <TitleH2>Propriété intellectuelle</TitleH2>
    <p>L'ensemble du contenu présent sur ce site, y compris, mais sans s'y limiter, les textes, les images, les vidéos, les graphiques, les logos et les éléments interactifs, est la propriété exclusive de Frynge ou de ses concédants de licence, et est protégé par les lois nationales et internationales sur la propriété intellectuelle.</p>
    <TitleH2>Signalement de violation</TitleH2>
    <p>Si vous estimez que vos droits de propriété intellectuelle ont été violés par le contenu de ce site, veuillez nous contacter immédiatement à l'adresse suivante: chloe.faye@mmibordeaux.com. Nous traiterons rapidement toute réclamation légitime et prendrons les mesures nécessaires.</p>
    <TitleH2>Utilisation Autorisée</TitleH2>
    <p>Les utilisateurs du site sont autorisés à accéder au contenu et à l'utiliser à des fins personnelles, éducatives et non commerciales. Toute utilisation contraire à ces termes est expressément interdite.</p>
    <TitleH2>Exactitude des informations</TitleH2>
    <p>Frynge s'efforce de fournir des informations exactes et à jour sur ce site, mais ne donne aucune garantie quant à l'exactitude, l'exhaustivité ou la pertinence des informations fournies. L'utilisation des informations disponibles sur ce site se fait à vos propres risques.</p>
    <p>Frynge se réserve le droit de modifier, supprimer ou mettre à jour tout contenu à tout moment sans préavis. Il incombe à l'utilisateur de vérifier régulièrement les informations disponibles sur ce site pour s'assurer de leur pertinence et de leur actualité.</p>
    <TitleH2>Conseils et Astuces</TitleH2>
    <p>Les conseils, astuces et informations fournies sur ce site sont destinés à des fins éducatives et informatives seulement. Ils ne doivent pas être interprétés comme des conseils professionnels ou médicaux. Avant de prendre des décisions basées sur les informations fournies sur ce site, il est recommandé de consulter des professionnels qualifiés pour des conseils spécifiques à votre situation.</p>
    <TitleH2>Responsabilités limitées</TitleH2>
    <p>Frynge décline toute responsabilité quant aux dommages directs, indirects, spéciaux, consécutifs ou autres qui pourraient résulter de l'utilisation ou de l'interprétation des informations fournies sur ce site.</p>
    <TitleH2>Signalement d’inexactitudes</TitleH2>
    <p>Si vous identifiez des informations que vous estimez inexactes, obsolètes ou incomplètes, veuillez nous contacter à l'adresse suivante : chloe.faye@mmibordeaux.com. Nous ferons les efforts nécessaires pour corriger toute inexactitude dans les plus brefs délais.</p>

</section> 

<style>
    section{
        width: 100vw;
        padding-left: 5rem;
        padding-right: 5rem;
    }
    @media screen and (max-width: 450px) {
        section{
        padding-left: 1rem;
        padding-right: 1rem;
    }
    }
    


</style>