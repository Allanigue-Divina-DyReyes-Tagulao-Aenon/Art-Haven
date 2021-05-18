// Create.vue 

<template>
    <div>
        <h2 class="title">Traditional Arts</h2>
        <img class="J" src="lastsupper.jpg">
        <p id="J1" class="descrip1"><b>The Last Supper</b> Italian Cenacolo, one of the most famous artworks in the world, painted by Leonardo da Vinci probably between 1495 and 1498 for the Dominican monastery Santa Maria delle Grazie in Milan. It depicts the dramatic scene described in several closely connected moments in the Gospels, including Matthew 26:21–28, in which Jesus declares that one of the Apostles will betray him and later institutes the Eucharist. According to Leonardo’s belief that posture, gesture, and expression should manifest the “notions of the mind,” each one of the 12 disciples reacts in a manner that Leonardo considered fit for that man’s personality. The result is a complex study of varied human emotion, rendered in a deceptively simple composition.</p>
        <img class="mona" src="monalisa.jpg">
        <p id="M1" class="descrip2"><b>The Mona Lisa</b> da Vinci began painting the Mona Lisa about 1503, and it was in his studio when he died in 1519. He likely worked on it intermittently over several years, adding multiple layers of thin oil glazes at different times. Small cracks in the paint, called craquelure, appear throughout the whole piece, but they are finer on the hands, where the thinner glazes correspond to Leonardo’s late period.</p>
        <img class="star" src="starrynight.jpg">
        <p id="SN1" class="descrip3"><b>Starry Night</b> Vincent van Gogh painted The Starry Night in 1889 while he was staying in Saint-Paul asylum in Saint-Rémy, France, where he lived for a year following a breakdown and the mutilation of his left ear. Painted with oil on canvas, the artist attempted to capture the view from the window in his room.</p>
        <img class="pic" src="picasso.jpg">
        <p id="P1" class="descrip4"><b>Guernica</b> a large black-and-white oil painting executed by Spanish artist Pablo Picasso in 1937 following the German bombing of Guernica, a city in Spain’s Basque region. The complex painting received mixed reviews when it was shown in the Spanish Republic Pavilion at the world’s fair in Paris, but it became an icon as it traveled the world in ensuing years, raising controversies on its meaning and its rightful home.</p>
        <img class="G" src="girl.jpg">
        <p id="G1" class="descrip5"><b>Girl with the Pearl Earrings</b> oil painting on canvas (c. 1665) by Dutch artist Johannes Vermeer, one of his most well-known works. It depicts an imaginary young woman in exotic dress and a very large pearl earring. The work permanently resides in the Mauritshuis museum in The Hague. Girl with a Pearl Earring represents a young woman in a dark shallow space, an intimate setting that draws the viewer’s attention exclusively on her. She wears a blue and gold turban, the titular pearl earring, and a gold jacket with a visible white collar beneath.</p>
        <img class="ele" src="elephant.jpg">
        <p id="E1" class="descrip6"><b>The Elephant</b> is a recurring theme in the works of Dalí, first appearing in his 1944 work Dream Caused by the Flight of a Bee Around a Pomegranate a Second Before Awakening, and also in The Temptation of Saint Anthony and Swans Reflecting Elephants</p>
    </div>
    
</template>
<script>
export default {

}
</script>
<style>
.title{
    font-family: helvetica;
    font-size: 55px;
    position: absolute;
    top: 265px;
    left: 39%;
}
.J{
    width: 25%;
    top: 360px;
    position: absolute;
}
.descrip1{
    width: 49%;
    top: 370px;
    position: absolute;
    left: 50%;
}
.mona{
    width: 15%;
    top: 600px;
    position: absolute;
    left: 15%;
}
.descrip2{
    width: 49%;
    top: 690px;
    position: absolute;
    left: 39%;
}
.star{
    width: 20%;
    top: 960px;
    position: absolute;
    left: 15%;
}
.descrip3{
     width: 49%;
    top: 1050px;
    position: absolute;
    left: 39%;
}
.pic{
    width: 28%;
    top: 1230px;
    position: absolute;
    left: 15%;
}
.descrip4{
    width: 49%;
    top: 1260px;
    position: absolute;
    left: 45%;
}
.G{
    width: 15%;
    top: 1430px;
    position: absolute;
    left: 20%;
}
.descrip5{
    width: 49%;
    top: 1470px;
    position: absolute;
    left: 39%; 
}
.ele{
   width: 15%;
    top: 1730px;
    position: absolute;
    left: 20%; 
}
.descrip6{
    width: 49%;
    top: 1830px;
    position: absolute;
    left: 39%; 
}

</style>