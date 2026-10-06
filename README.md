# Demo — Hotel Pousada GuaruBora

Site demo para o **Hotel Pousada GuaruBora** (Praia da Boracéia, São Sebastião – SP).
HTML, CSS e JS puro, sem build. Feito para proposta comercial.

## Como editar

- **Dados** (nome, WhatsApp, telefone, endereço, horários, preços, políticas, fotos): objeto `CONFIG` no início do `<script>`, no final do `index.html`.
- **WhatsApp**: hoje está o fixo da recepção (`551238671770`). Trocar pelo celular do hotel em `CONFIG.whatsapp`.
- **Cores**: variáveis no `:root` do CSS (`--noite`, `--mar`, `--manga`, `--nevoa`).
- **Fontes**: Fraunces (títulos) + Figtree (texto), do Google Fonts.
- **Fora do CONFIG** (ficam fixos no `<head>`, porque o WhatsApp e o Google não rodam JS):
  tags Open Graph (`og:*`) e o JSON-LD `LodgingBusiness`. Se o domínio mudar, atualize as URLs `https://demo-guarubora.vercel.app/` nos dois.

## O que é de exemplo (confirmar com o hotel)

- **Depoimentos**: são **de exemplo**, escritos a partir do que os hóspedes elogiam nas avaliações reais (lugar tranquilo e familiar, estrutura limpa, piscina, atendimento do dono e da recepção, perto da praia, restaurante). Nomes fictícios.
- **Preços** (R$ 290 / 420 / 480), **comodidades dos quartos** e **capacidades**.
- **Horários do restaurante** (café 7h30–10h, almoço 12h–16h).
- **Check-in 14h / check-out 12h**, política de **crianças** e **pets**.
- **Distâncias**: calculadas por rota no OpenStreetMap (OSRM), arredondadas — Bertioga ≈ 38 km, São Paulo ≈ 135 km, São José dos Campos ≈ 140 km.
- **Fotos**: banco de imagens (não são do hotel). Trocar pelas fotos reais assim que possível.

Dados reais usados: nome, endereço, telefone da recepção, horário da recepção (9h–17h), nota 4,4 com 200+ avaliações no Google, restaurante e café da manhã abertos ao público.

## Fotos — créditos

Todas do [Unsplash](https://unsplash.com/license) (licença Unsplash: uso livre, comercial inclusive, sem necessidade de atribuição — créditos registrados por boa prática).
Convertidas para WebP em duas larguras (`*.webp` 1600px e `*-sm.webp` 800px). `og.jpg` (1200×630) é um recorte de `hero.webp`.

| Arquivo | Autor | Link |
|---|---|---|
| `hero.webp` | [Agnaldo Andrella](https://unsplash.com/pt-br/@andrella) | [Unsplash](https://unsplash.com/pt-br/fotografias/arvore-verde-na-praia-de-areia-branca-durante-o-dia-O8O9L0cqCoI) |
| `praia-mata.webp` | [Nathalia Segato](https://unsplash.com/pt-br/@trintaycinco) | [Unsplash](https://unsplash.com/pt-br/fotografias/pessoas-em-pe-na-costa-perto-de-arvores-durante-o-dia-P7SvhMwfVd0) |
| `familia-praia.webp` | [Mehdi Benkaci](https://unsplash.com/pt-br/@mehdibck) | [Unsplash](https://unsplash.com/pt-br/fotografias/familia-de-quatro-pessoas-em-pe-a-beira-mar-b8ZLTaFaD4Y) |
| `familia-mar.webp` | [Natalya Zaritskaya](https://unsplash.com/pt-br/@goodmood77) | [Unsplash](https://unsplash.com/pt-br/fotografias/man-woman-and-child-holding-hands-on-seashore-SIOdjcYotms) |
| `quarto-casal.webp` | [Point3D Commercial Imaging Ltd.](https://unsplash.com/pt-br/@3dottawa) | [Unsplash](https://unsplash.com/pt-br/fotografias/roupa-de-cama-branca-na-cama-_Swg04CP0bU) |
| `quarto-familia.webp` | [Masaaki Komori](https://unsplash.com/pt-br/@gaspanik) | [Unsplash](https://unsplash.com/pt-br/fotografias/travesseiro-branco-da-cama-na-cama-iMbXscxYIFE) |
| `suite-superior.webp` | [Antonio Araujo](https://unsplash.com/pt-br/@antonioaaaraujo) | [Unsplash](https://unsplash.com/pt-br/fotografias/garrafa-de-vinho-e-tacas-na-mesa-com-vista-para-o-oceano-R1NdTGhd9eM) |
| `piscina.webp` | [atman studios](https://unsplash.com/pt-br/@atmanstudios) | [Unsplash](https://unsplash.com/pt-br/fotografias/cadeiras-dobraveis-de-madeira-marrom-perto-da-piscina-durante-o-dia-UPolqOrkbno) |
| `piscina-jardim.webp` | [No ExpressioN](https://unsplash.com/pt-br/@nox262) | [Unsplash](https://unsplash.com/pt-br/fotografias/piscina-azul-rTjXnpihyOU) |
| `rede.webp` | [Florian Siedl](https://unsplash.com/pt-br/@szie) | [Unsplash](https://unsplash.com/pt-br/fotografias/um-homem-deitado-em-um-rede-com-um-chapeu-dzHf7j-7fes) |
| `restaurante.webp` | [Kate Trysh](https://unsplash.com/pt-br/@katetrysh) | [Unsplash](https://unsplash.com/pt-br/fotografias/uma-area-de-jantar-ao-ar-livre-com-mesas-e-cadeiras-KRXX14JyFaY) |
| `moqueca.webp` | [Travis](https://unsplash.com/pt-br/@tvieso) | [Unsplash](https://unsplash.com/pt-br/fotografias/uma-tigela-de-sopa-com-uma-colher-IGsSbLoTkro) |
| `peixe.webp` | [Keesha's Kitchen](https://unsplash.com/pt-br/@keeshasskitchen) | [Unsplash](https://unsplash.com/pt-br/fotografias/um-prato-de-peixe-e-limoes-KRbF_wsztBE) |
| `prato-feito.webp` | [Zulu Fernando](https://unsplash.com/pt-br/@zulufernando) | [Unsplash](https://unsplash.com/pt-br/fotografias/comida-cozida-na-placa-de-ceramica-branca-YCIsQDGfd40) |
| `cafe-mesa.webp` | [Dad hotel](https://unsplash.com/pt-br/@dadhotel) | [Unsplash](https://unsplash.com/pt-br/fotografias/frutas-fatiadas-em-placa-de-ceramica-branca-ao-lado-de-caneca-de-ceramica-branca-com-cafe-O8z4jAZVQQE) |
| `tapioca.webp` | [igor constantino](https://unsplash.com/pt-br/@igoorconstantino) | [Unsplash](https://unsplash.com/pt-br/fotografias/um-prato-branco-coberto-com-um-sanduiche-ao-lado-de-uma-xicara-de-cafe-koK_vmMKhfU) |
| `buffet.webp` | [Holiday Extras](https://unsplash.com/pt-br/@holidayextras) | [Unsplash](https://unsplash.com/pt-br/fotografias/mulher-escolhendo-doces-de-uma-vitrine-de-buffet-y6xXt58nywQ) |

## Publicar

```bash
vercel project add demo-guarubora
vercel deploy --prod --yes --project demo-guarubora
```
