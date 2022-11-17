---
layout: post
title: "Place, Perspective, and Time"
permalink: /land-acknowledgement
project: "Visual Land Acknowledgement"
tag: coloured-pencil
---

<p id="acknowledgement">I acknowledge the traditional Coast Salish territories of the Semiahmoo, Tsawwassen, Kwantlen, and Katzie First Nations on which I live, play, and learn. I recognize the importance of understanding the history of this land, and I pledge my role in the ongoing works toward reconciliation. I hope that, through learning, my artworks can reflect and honour the traditional teachings of Coast Salish peoples.</p>

<input type="checkbox" id="btnControl" />
<label for="btnControl">
    <img width="100%" id="artwork" src="assets/images/visual_land_acknowledgement/visual_land_acknowledgement.png" />
</label>

_Hover/click on the artwork to see it shift. Own work._

This piece is centred around perspective. A distinct brick building stands out among the vibrant green landscape; this is my school. It is where I spend most of my day for most of the year, and it is very much a representation of the life I currently live.

For me, my school is a place where I can spend time with my friends and expand my knowledge of the world. However, for many Indigenous children of the past, schools were a place where they were subjected to physical and emotional torture.

While the school acts to symbolize my life, it also encourages the viewer to reflect and acknowledge the atrocities committed in residential schools of Canada and its lasting effects of direct and intergenerational trauma for many Indigenous people today.

Surrounding the building are landscapes of the Pacific Northwest. This demonstrates the interconnectedness between the land, its history, and my life. It also acknowledges the relationship first peoples have had and continue to have with this land and, by extension, their connection to my life and me.

Water is a central element throughout the piece. On one end lies the beach: a representation of the connection Coast Salish peoples, particularly the Semiahmoo and Tsawwassen First Nations, have with the Salish Sea. Then, the water stretches through a river into a lake, acknowledging the traditional importance of river and fishing to first peoples, particularly the Kwantlen and Katzie First Nations.

The piece only allows the viewer to see all its parts when they actively rotate the image. This demonstrates the insight we gain by expanding our perspectives but also underscores the fact that we must make a conscious effort to do so. In practice, it represents the fact that to create a society that empowers and cherishes every person, we all must make an effort to understand the history and presence of first peoples on the land we live in.

<style>
    #acknowledgement{
        font-family: "Lora", serif;
        margin: 1rem 0;
    }

    #artwork {
        -moz-transition: transform 7s;
        -webkit-transition: transform 7s;
        transition: transform 7s;
    }

    @media (hover: hover) {
        #artwork:hover {
            transform: rotate(183deg);
            -moz-transform: rotate(183deg);
            -webkit-transform: rotate(183deg);
        }
    }

    #btnControl {
        display: none;
    }

    #btnControl:checked+label>img {
        transform: rotate(183deg);
        -moz-transform: rotate(183deg);
        -webkit-transform: rotate(183deg);
    }
</style>
