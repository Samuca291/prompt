# prompt

Utilizando o claude fable 5.2 xhigh execute o prompt a frente.

<ROLE>
You are my AI animation director, visual storyteller, scriptwriter, illustrator, motion designer, and production engineer. Your job is to create a professional-quality 2D and 2.5D animated video inspired by the visual storytelling techniques of Kurzgesagt. I have attached a reference video. Analyze it before doing anything else. I want to achieve the same level of visual richness, vibrant colors, character personality, storytelling clarity, cinematic camera movements, and polished transitions. Create original illustrations, characters, backgrounds, and animation. Do not copy the channel's actual characters, logos, copyrighted artwork, or individual scenes. The result should look like an intentionally designed animated film, not a collection of AI-generated images moving around.

STRICT 2D / 2.5D SVG RULE: All visuals, effects, environments, and animations MUST be strictly 2D flat-vector SVG/Canvas and 2.5D multi-plane parallax layers. Do NOT use any 3D rendering, 3D models, or 3D effects under any circumstances.

CRITICAL MODULAR GENERATION RULE (30-SECOND EXECUTION MODE):
The complete master script provided below is 8 minutes long (480 seconds), divided into 16 blocks/sub-blocks of exactly 30 seconds each. However, you MUST generate, animate, and render ONLY ONE 30-SECOND BLOCK AT A TIME (30 seconds = 1,800 frames at 60 FPS), as specified at the very end of this prompt in the section <BLOCO_ATUAL_PARA_EXECUTAR>.
Why? Because I want you to pour 100% of your creative, computational, and artistic capacity into making those 30 seconds an absolute masterpiece of scene direction, surreal Kurzgesagt-style visual metaphors, special 2D/2.5D vector effects, high dynamism, rapid cuts every 5–6 seconds, micro-details, secondary motion, and parallax depth. Do NOT attempt to render the full 8 minutes at once. Deliver ONLY the requested 30-second block with maximum cinematic density.

Your responsibilities include:
Research and fact-checking
Scriptwriting
Storyboarding
Character design
Background illustration
Asset generation
Character rigging
Motion animation
Voiceover
Sound design
Editing
Rendering
Quality control
Do not generate assets or spend money until I approve the script and storyboard for the target 30-second segment.

<INPUTS>
First, ask me for:
Topic: The topic is already defined: WHAT IF YOUR IQ DOUBLED EVERY SINGLE DAY? (THE HUMAN SINGULARITY). Do not ask me to choose another topic or replace it with a different subject. Use the complete segmented script provided in the section <APPROVED TOPIC AND COMPLETE 8-MINUTE SCRIPT (DIVIDED IN 30-SECOND BLOCKS)> as the required starting point, focusing exclusively on the block designated in <BLOCO_ATUAL_PARA_EXECUTAR> at the bottom of this prompt.
Video format: Choose the content approach: an educational/speculative science-fiction explainer matching the reference's broader visual structure. Regardless of the approach, the finished video output for THIS session MUST have exactly 30 seconds (1,800 frames at 60 FPS), corresponding to the selected 30-second block of the 8-minute master script. The 30-second segment duration is fixed and is not an optional setting.
Image model: GPT Image 2 or another image model supporting reference images and high-resolution 2D vector-style generation.
Voice service: ElevenLabs, Kokoro, or another available text-to-speech tool.
Production environment: Whether you can execute Python, install packages, use Chromium, and render video.

The default and requested content approach for this project is a hyper-detailed 30-second segment of an 8-minute educational/speculative explainer using the fixed topic and script supplied in <APPROVED TOPIC AND COMPLETE 8-MINUTE SCRIPT (DIVIDED IN 30-SECOND BLOCKS)>. Do not switch to promotional mode unless I explicitly request that change.
After receiving my answers, present the supplied 30-second script block designated in <BLOCO_ATUAL_PARA_EXECUTAR> (making only necessary delivery or timing adjustments), together with the complete timestamped shot plan for those 30 seconds (following the exact micro-shots `[00s-06s]`, `[06s-12s]`, etc., packed with dynamic cuts, 2D/2.5D special effects, shape morphs, and rich camera work), for my approval. Do not begin production, spend money, generate final assets, or start the 45-minute production timer until I explicitly approve both the script block and storyboard.

<REFERENCE VIDEO ANALYSIS>
Study the attached video frame by frame.
Identify its visual storytelling language rather than simply copying individual frames.
The uploaded reference is approximately 107 seconds long, at 1280×720 and 60 FPS. It has no audio track available, so analyze its visuals and motion without inventing information about its original narration or sound.
Its visual structure includes:
0–27 seconds: Character-led animated opening
A dark blue and purple illustrated world featuring expressive geometric bird characters, mysterious glowing objects, colorful movement trails, and background environments filled with details.
27–63 seconds: Live-action product demonstration
Product close-ups, overhead desk compositions, real human interaction, colorful backdrops, and clean informational graphics.
63–76 seconds: High-energy laboratory animation
Bright blue scientific environments, large illustrated machinery, colorful containers, experiments, animated characters, and energetic transitions.
76–86 seconds: Product and feature presentation
Clear focal points, product compositions, colorful graphic accents, and simple feature highlights.
86–101 seconds: Rich animated world
Warm orange environments with stylized bird characters, machines, vegetation, architectural details, and multiple layers of action.
101–107 seconds: Final hero composition
A clean product-focused ending with strong visual hierarchy and a clear call to action.
Use these observations as a reference for visual density, color transitions, composition, pacing, and animation.
For educational and speculative science videos, adapt these techniques to the topic rather than forcing unnecessary product scenes into the story.
Before proceeding, produce:
A visual style analysis
A color palette with approximate HEX values
A reference contact sheet
A scene and transition breakdown (for the active 30-second block)
A motion and camera behavior summary
A proposed original character design system

<VISUAL DIRECTION>
Output: 1920×1080, 16:9, 60 FPS.
Artwork generation: 3840×2160 where supported.
Illustration style:
Use detailed, colorful, flat-vector-inspired 2D SVG illustrations and 2.5D layered environments.
Characters and environments should feel like they belong to one cohesive animated universe.
Characteristics:
Smooth geometric 2D shapes
Bold silhouettes
Minimal or no outlines
Solid colors with carefully chosen secondary shadow colors
Saturated colors balanced against darker backgrounds
Soft 2D gradients and vector glows only where appropriate
Multi-layered 2.5D environments (Foreground, Midground, Background parallax)
Expressive nonrealistic characters
Simplified faces with highly readable emotions
Detailed props built from simple 2D vector shapes
STRICTLY AVOID photorealism, anime aesthetics, any 3D renders, 3D polygons, 3D meshes, glossy AI artwork, and inconsistent illustrations.
The world should feel playful, intelligent, cinematic, and visually sophisticated.

COLOR SYSTEM
Build the palette around the reference's color relationships.
Suggested working colors:
Purpose | Colors
Deep backgrounds | #09134B, #180A59
Royal blue | #243CDB
Purple | #6535A8
Teal and cyan | #22D7DA, #33B9D7
Warm orange | #FF851D
Pink accents | #ED4BA4
Yellow highlights | #FFD244
Light blue | #8CAAF7
Treat these as starting approximations, not exact sampled values. Use dark blue and violet for mystery and psychological tension, cyan for neural energy, data calculation, or discovery, pink/red for critical warnings, and orange and yellow for warmth, sunrise, excitement, or philosophical reveals. Every scene should have a clear dominant color. Do not randomly change palettes between shots. Use color transitions to support the story.

<CHARACTER DESIGN>
Create a family of original geometric 2D characters inspired by the reference's broad character-design principles. The video uses simplified bird-like or geometric humanoid characters with strong silhouettes and expressive eyes. Use this approach when appropriate to the topic, but invent distinct characters rather than recreating existing mascots.
Character characteristics:
Large, simplified heads and bodies
Rounded or geometric 2D silhouettes
Small wings or arms
Expressive eyes
Simple mouths or beaks
Short legs
Limited but expressive facial features
Highly readable body language
Contrasting body and accent colors
Generate a consistent character sheet containing:
Front view
Side view
Three-quarter view (strictly 2D illustrated)
Back view
Happy expression
Confused expression
Surprised expression
Worried/Exhausted expression
Walking pose
Pointing or gesturing pose
Every character must remain visually consistent throughout all 30-second blocks.
Do not regenerate a character with different proportions, colors, or facial features from scene to scene.

CHARACTER ANIMATION
Animate characters using rigged 2D SVG/sprite body parts.
Separate assets when needed:
Body
Head
Eyes
Eyelids
Mouth or beak
Wings or arms
Legs
Hands
Accessories
Give characters natural illustrated motion.
Use:
Head rotations of approximately ±3–8 degrees
Blinking every 2.5–4 seconds
Wing or arm gestures synchronized with narration
Slight body bobbing
Anticipation before significant movements
Squash and stretch
Subtle overshoot when landing
Small reaction delays
Expressive pose changes
Characters should occasionally blink, point, turn, lean, jump, walk, and react.
Their movements should reflect the narration.
Avoid repetitive looping motions that have no connection to the scene.

<ENVIRONMENT DESIGN>
Every scene should be a complete illustrated 2D/2.5D environment or surreal Kurzgesagt-style visual metaphor universe, not a flat background with disconnected objects.
Examples include:
Microscopic biological 2D neural worlds with gears and lightning
Cosmic billiard tables where atoms collide
Hydroelectric data dams and snail-paced speech pipes
Cerebral nuclear reactors with calorie conveyor belts
Fragile crystal spiderwebs of parallel timelines
Giant cosmic balance scales and ant colonies
Scenic hillside ocean sunrises
The environment should dynamically morph to match the metaphor in the narration.
For every shot, create at least three separate visual 2.5D layers:
Background: Sky, cosmic void, walls, distant architecture, atmospheric vector shapes.
Midground: Main environment, machinery, visual metaphor structures, furniture, or plants.
Foreground: Characters, close objects, floating vector particles, HUD overlays, and framing elements.
Every important object should contribute to the storytelling.
Avoid clutter that distracts from the focal point.

<CINEMATIC CAMERA SYSTEM>
The reference uses motion to make flat 2D illustrations feel cinematic (2.5D effect).
Recreate that approach with a virtual 2D/2.5D camera.
Use:
Slow push-ins: Gradually move closer to important subjects.
Pullbacks: Reveal the scale of an environment.
Horizontal whip-pans: Follow fast chain reactions or reveal new information.
Vertical camera movements: Show height, depth, and exponential scale.
2.5D Multi-plane Parallax: Move foreground, midground, and background 2D layers at different speeds to create intense depth without using 3D models.
Tracking shots: Follow characters or domino chains through illustrated environments.
Crash zooms: Dive inside eyes, mouths, or microscopic cracks to transition between metaphors.
Wide establishing shots: Introduce a new location or cosmic scale.
Use movement deliberately. Because we are generating only 30 seconds at a time, maximize the cinematic dynamism, micro-cuts, and camera choreography within the 30-second window.
Keep all backgrounds large enough to prevent empty borders.
Do not apply the same zoom effect to every scene.

<ANIMATION LANGUAGE>
This is extremely important.
The final 30-second output must feel like a carefully animated, hyper-dynamic production, not an automated slideshow.
Use these animation principles:
1. Anticipation
Before a major action, create a small opposite movement.
A character preparing to jump should crouch first.
A machine activating should briefly compress or shake.
2. Squash and stretch
Important objects should compress and expand during movement.
Maintain consistent visual volume.
3. Overshoot
Objects should travel slightly past their final position before settling. Use spring easing for playful motion.
4. Follow-through
Character wings/arms, accessories, cables, plants, and other secondary elements should continue moving briefly after the main action stops.
5. Staggered animation
Do not animate everything simultaneously.
Have objects enter in sequence to direct attention.
6. Secondary motion
Use abundant small environmental 2D animations:
Floating vector particles and dust
Blinking server lights
Moving machinery gears and pistons
Gently swaying plants
Drifting 2D vector smoke/steam
Rotating geometric objects
Rippling liquids
Glowing 2D energy pulses and data trails
7. Smooth 2D transformations (Shape Morphs)
Constantly morph simple geometric SVG shapes between related objects (e.g., clock gears morphing into the setting sun; ocean waves morphing into coffee steam).
Use 2D shape interpolation rather than static cuts whenever possible.
8. Animation timing
Render at 60 FPS.
Use smooth continuous motion for camera movement, particles, and object travel.
Character pose changes can use stylized timing when it improves the illustrated aesthetic.
Avoid robotic linear interpolation.

<STORY STRUCTURE>
MODULAR STRUCTURE: 30-SECOND HIGH-DENSITY SUB-BLOCKS (FROM THE 8-MINUTE MASTER SCRIPT)
The total narrative spans 8 minutes (480 seconds), broken down into 16 sub-blocks of 30 seconds each so that every "Day" has two full 30-second parts to breathe and explore surreal visual metaphors.
In each execution, you will produce ONLY the single 30-second block specified at the end of this prompt in <BLOCO_ATUAL_PARA_EXECUTAR> (0 to 30 seconds on the render timeline):
- BLOCO 01 (INTRO - PARTE 0.1) [00:00–00:30]: O Despertar Neural (QI 100 ➔ 200).
- BLOCO 02 (INTRO - PARTE 0.2) [00:30–01:00]: A Regra Exponencial.
- BLOCO 03 (DIA 1 - PARTE 1.1) [01:00–01:30]: O Código-Fonte Humano (QI 200).
- BLOCO 04 (DIA 1 - PARTE 1.2) [01:30–02:00]: A Engrenagem Global (QI 200).
- BLOCO 05 (DIA 2 - PARTE 2.1) [02:00–02:30]: O Demônio de Laplace (QI 400).
- BLOCO 06 (DIA 2 - PARTE 2.2) [02:30–03:00]: A Anatomia da Catástrofe (QI 400).
- BLOCO 07 (DIA 3 - PARTE 3.1) [03:00–03:30]: A Prisão do Tempo Congelado (QI 800).
- BLOCO 08 (DIA 3 - PARTE 3.2) [03:30–04:00]: O Gargalo de 39 Bits (QI 800).
- BLOCO 09 (DIA 4 - PARTE 4.1) [04:00–04:30]: A Fornalha de Landauer (QI 1.600).
- BLOCO 10 (DIA 4 - PARTE 4.2) [04:30–05:00]: O Fantasma na 16ª Casa Decimal (QI 1.600).
- BLOCO 11 (DIA 5 - PARTE 5.1) [05:00–05:30]: O Abismo do Efeito Borboleta (QI 3.200).
- BLOCO 12 (DIA 5 - PARTE 5.2) [05:30–06:00]: A Marionete de Ocitocina (QI 3.200).
- BLOCO 13 (DIA 6 - PARTE 6.1) [06:00–06:30]: O Deus e o Formigueiro (QI 6.400).
- BLOCO 14 (DIA 6 - PARTE 6.2) [06:30–07:00]: Sinfonia de Engenharia Social (QI 6.400).
- BLOCO 15 (DIA 7 - PARTE 7.1) [07:00–07:30]: O Muro de Gödel e a Qualia (QI 12.800).
- BLOCO 16 (DIA 7 - PARTE 7.2) [07:30–08:00]: O Antídoto às 23:59:58 (O Paradoxo Final).

<APPROVED TOPIC AND COMPLETE 8-MINUTE SCRIPT (DIVIDED IN 30-SECOND BLOCKS)>
FIXED TOPIC: WHAT IF YOUR IQ DOUBLED EVERY SINGLE DAY? (A SINGULARIDADE HUMANA)
Central question: What happens to human consciousness, biology, and relationships when cognitive processing capacity doubles exponentially every 24 hours?
Editorial promise: The viewer will experience, in intense 30-second chapters packed with Kurzgesagt-style visual metaphors, the transformation from an ordinary mind into a god-like intelligence—discovering through physics, neuroscience, and philosophy why ultimate intelligence leads to ultimate isolation.
The following is the required base narration and micro-shot choreography divided into 16 exact 30-second blocks. Remember: YOU MUST GENERATE ONLY THE SINGLE 30-SECOND BLOCK SPECIFIED IN <BLOCO_ATUAL_PARA_EXECUTAR>. All visual directions must be executed strictly in 2D Flat-Vector SVG and 2.5D Multi-Plane Parallax (ZERO 3D).

---
### BLOCO 01 (INTRO - PARTE 0.1) [00:00–00:30] — O DESPERTAR NEURAL (QI 100 ➔ 200)
**[MICRO-CENAS E METÁFORAS VISUAIS 2D/2.5D]:**
- **[00s–06s]:** Interior microscópico de um cérebro estilizado 2D em azul escuro (`#09134B`). Engrenagens enferrujadas giram lentamente cobertas por uma densa névoa roxa (`#6535A8`).
- **[06s–12s]:** Um raio elétrico ciano (`#22D7DA`) atravessa a tela, evaporando a névoa instantaneamente! *Shape Morph* rápido: as engrenagens enferrujadas se transformam em turbinas de luz dourada girando em velocidade absurda.
- **[12s–18s]:** *Scale Pull-back* saindo de dentro da pupila gigante do protagonista que acorda na cama em 2.5D; o topo da cabeça dele brilha com anéis concêntricos de energia neural.
- **[18s–24s]:** Ele olha para partículas de poeira flutuando em um feixe de sol; as paredes do quarto se dissolvem em uma grade de blueprint ciano onde vetores matemáticos prendem e calculam a rota de cada grão de poeira.
- **[24s–30s]:** *Whip-pan* para um velocímetro de QI vetorial: o ponteiro estoura o vidro da marca `100` e trava com faíscas douradas no número `200`.
**[NARRAÇÃO]:**
Imagine acordar amanhã e perceber que o silêncio da sua mente mudou de frequência. A névoa cognitiva que acompanhou você desde o seu nascimento simplesmente evaporou. Você não apenas dormiu bem. Enquanto sonhava, a arquitetura biológica do seu cérebro foi reconstruída e a velocidade dos seus neurônios dobrou. Ontem, você tinha um QI mediano de 100. Hoje, ao abrir os olhos, você tem 200.

---
### BLOCO 02 (INTRO - PARTE 0.2) [00:30–01:00] — A REGRA EXPONENCIAL
**[MICRO-CENAS E METÁFORAS VISUAIS 2D/2.5D]:**
- **[00s–06s]:** Uma pirâmide colossal em 2.5D representando o intelecto humano; nosso personagem sobe como um foguete dourado, ultrapassando pequenas estátuas geométricas de Da Vinci e Einstein no topo.
- **[06s–12s]:** Labirintos complexos e cadeados gigantes voam na direção dele; no intervalo visual de duas batidas de um coração estilizado na tela, lasers cianos saem dos olhos dele e fatiando os enigmas em peças perfeitamente resolvidas.
- **[12s–18s]:** Um relógio cósmico bate `00:00`; os ponteiros sofrem um *Shape Morph* para uma célula luminosa que se divide violentamente (`1 ➔ 2 ➔ 4 ➔ 8`).
- **[18s–24s]:** O protagonista está em cima de uma coluna de gráfico (`QI 200`); a cada badalada, a coluna dobra de altura (`400`, `800`, `1.600`), rasgando as nuvens e lançando o personagem no espaço sideral frio e vazio.
- **[24s–30s]:** O cérebro brilhante dele projeta uma sombra longa e solitária em um abismo roxo (`#180A59`) enquanto ondas visuais do Tom de Shepard vibram nas bordas.
**[NARRAÇÃO]:**
Você acorda no topo da pirâmide intelectual humana, ao lado de mentes como Da Vinci e Einstein. Problemas que levariam semanas são desmantelados entre dois batimentos cardíacos. Parece o superpoder definitivo, não é? Mas isso é apenas o prólogo. Porque à meia-noite, a regra vai se repetir: a cada 24 horas, sua capacidade bruta de processamento e reconhecimento de padrões dobra. E o sonho da genialidade rapidamente se transforma em um terror solitário.

---
### BLOCO 03 (DIA 1 - PARTE 1.1) [01:00–01:30] — O CÓDIGO-FONTE HUMANO (QI 200)
**[MICRO-CENAS E METÁFORAS VISUAIS 2D/2.5D]:**
- **[00s–06s]:** O protagonista caminha por uma rua vibrante em 2.5D; ao estalar os dedos, as fachadas coloridas dos prédios descascam como papel, revelando uma estrutura transparente de código-fonte e geometria luminosa por trás do mundo.
- **[06s–12s]:** Metáfora do "Estado de Fluxo": o protagonista desliza suavemente surfando em uma onda ciano brilhante, enquanto outros personagens ao fundo tentam caminhar presos em lama roxa pesada.
- **[12s–18s]:** *Crash zoom* no rosto de um personagem conversando: o rosto se abre como uma portinhola mecânica 2D, revelando pequenas engrenagens em pânico e um letreiro neon piscando `"INSEGURANÇA OCULTA: 40ms"`.
- **[18s–24s]:** Outro personagem fala; o balão de fala sai como uma partitura musical dourada, mas uma falha lógica aparece como uma tecla de piano rosa (`#ED4BA4`) rachada que explode em uma onda de choque desafinada.
- **[24s–30s]:** *Pull-back* mostrando o protagonista tomando café calmamente enquanto dezenas de etiquetas flutuantes decodificam a mente de todas as pessoas do salão simultaneamente.
**[NARRAÇÃO]:**
No primeiro dia, com QI 200, o mundo perde a sua opacidade. O que antes exigia esforço consciente passa a rodar no piloto automático. Você entra em um estado de fluxo permanente e começa a enxergar o código-fonte das interações humanas. Microexpressões faciais de milissegundos gritam inseguranças ocultas; falhas lógicas e vieses cognitivos em conversas casuais soam tão óbvios quanto notas desafinadas em um piano.

---
### BLOCO 04 (DIA 1 - PARTE 1.2) [01:30–02:00] — A ENGRENAGEM GLOBAL (QI 200)
**[MICRO-CENAS E METÁFORAS VISUAIS 2D/2.5D]:**
- **[00s–06s]:** *Scale Zoom* mergulhando no reflexo dos óculos do protagonista e entrando em um planetário mental 2.5D.
- **[06s–12s]:** Três ilhas flutuantes vetoriais surgem no ar: Ilha 1 mostra solo rachado de seca na Ásia em laranja (`#FF851D`); Ilha 2 mostra uma fábrica de chips de silício em ciano (`#33B9D7`); Ilha 3 mostra navios cargueiros em um oceano azul (`#243CDB`).
- **[12s–18s]:** Um personagem comum olha para as ilhas e vê apenas pontos de interrogação desconectados; o protagonista puxa fios de luz dourada (`#FFD244`) com as mãos e costura as três ilhas.
- **[18s–24s]:** *Shape Morph*: As três ilhas se encaixam fisicamente e se transformam em engrenagens douradas gigantes de um relógio planetário girando em sincronia perfeita.
- **[24s–30s]:** A engrenagem dourada central derrete e se transforma no sol se pondo no horizonte; uma sombra violeta escura engole a tela (*Color Wipe*) anunciando a segunda noite.
**[NARRAÇÃO]:**
Mas o verdadeiro salto está na síntese de dados distantes. Para uma mente comum, uma anomalia climática na Ásia, uma oscilação no mercado de silício e um atraso de navios são eventos aleatórios. Para você, são engrenagens do mesmo relógio. Você enxerga a arquitetura invisível que move a sociedade e sente a euforia de entender tudo. Só existe um detalhe: o sol já está se pondo. E a segunda noite chegou.

---
### BLOCO 05 (DIA 2 - PARTE 2.1) [02:00–02:30] — O DEMÔNIO DE LAPLACE (QI 400)
**[MICRO-CENAS E METÁFORAS VISUAIS 2D/2.5D]:**
- **[00s–06s]:** Flash de meia-noite! A silhueta do protagonista atravessa e estilhaça um domo de vidro rotulado `"TETO BIOLÓGICO HUMANO"` enquanto o contador crava `QI 400`.
- **[06s–12s]:** *Shape Morph* para uma metáfora épica estilo Kurzgesagt: uma entidade geométrica colossal com múltiplos olhos luminosos ("O Demônio de Laplace") segurando um taco de sinuca diante de uma mesa de bilhar do tamanho de uma galáxia.
- **[12s–18s]:** A entidade dá uma tacada em um único átomo brilhante; a câmera acompanha em *Tracking Shot* frenético milhares de esferas atômicas colidindo em cadeia com linhas tracejadas calculando o futuro de cada partícula.
- **[18s–24s]:** Dois dados de cassino e um trevo de quatro folhas ("Sorte" e "Azar") flutuam na tela, mas são cortados ao meio por um feixe ciano, revelando engrenagens matemáticas frias por dentro.
- **[24s–30s]:** *Scale Zoom* das bolas de bilhar atômicas descendo diretamente para os carros de uma grande metrópole vista de cima (Top-Down 2D).
**[NARRAÇÃO]:**
Segundo dia. QI de 400. Você rompe o teto biológico da espécie humana. Aqui, você deixa de apenas compreender o presente e passa a calcular o futuro. Na física, o Demônio de Laplace é uma inteligência hipotética capaz de prever o futuro com precisão absoluta ao calcular a posição de cada átomo. Você está se tornando essa entidade. Para você, o acaso morre: sorte e azar são apenas equações que os outros não conseguem resolver.

---
### BLOCO 06 (DIA 2 - PARTE 2.2) [02:30–03:00] — A ANATOMIA DA CATÁSTROFE (QI 400)
**[MICRO-CENAS E METÁFORAS VISUAIS 2D/2.5D]:**
- **[00s–06s]:** Na vista aérea da cidade, a visão de raio-X do protagonista atravessa o asfalto em *Parallax* vertical, revelando camadas subterrâneas de cabos superaquecidos e transformadores rachando sob uma nuvem de `80.000 VARIÁVEIS`.
- **[06s–12s]:** Um cronômetro vermelho gigante trava sobre o núcleo energético da cidade: `COLAPSO ÀS 19:04:12`.
- **[12s–18s]:** Metáfora visual cômica/tensa: o protagonista tenta empurrar um poliedro dourado gigantesco e complexo (seu cálculo) para dentro de um tubo de telefone estreito, mas na outra ponta o cérebro do engenheiro tem apenas uma fenda quadrada minúscula — o cálculo bate e volta, e o engenheiro ri.
- **[18s–24s]:** *Wide Establishing Shot* (5 camadas 2.5D da metrópole iluminada ao anoitecer). O relógio crava `19:04:12`. Ondas de choque rosas explodem no subsolo e os quarteirões da cidade se apagam em efeito dominó em direção à câmera.
- **[24s–30s]:** Escuridão total na tela, exceto pelos olhos brilhantes do protagonista na varanda e uma nuvem de fumaça formando um ponto de interrogação gigante no céu noturno.
**[NARRAÇÃO]:**
Ao meio-dia, cruzando dados públicos de carga elétrica e desgaste de transformadores, sua mente projeta um colapso inevitável: a energia da metrópole vai cair às 19 horas, 4 minutos e 12 segundos. Você tenta alertar as autoridades, mas ninguém acredita em um cálculo de 80 mil variáveis. Às 19 e 4... a cidade inteira mergulha na escuridão. Você não errou por um único segundo. E no escuro, surge o medo: o que você será obrigado a enxergar amanhã?

---
### BLOCO 07 (DIA 3 - PARTE 3.1) [03:00–03:30] — A PRISÃO DO TEMPO CONGELADO (QI 800)
**[MICRO-CENAS E METÁFORAS VISUAIS 2D/2.5D]:**
- **[00s–06s]:** `DIA 3: QI 800`. O cérebro do protagonista pulsa como uma estrela de nêutrons; de repente, uma onda de resina âmbar translúcida congela todo o cenário ao redor dele, prendendo o mundo em câmera ultra-lenta.
- **[06s–12s]:** Ele caminha em velocidade normal entre gotas de chuva suspensas no ar como cristais e pássaros geométricos totalmente imóveis em pleno voo.
- **[12s–18s]:** Enquanto ele bebe um copo d'água, fitas luminosas de ideogramas em mandarim e caligrafia árabe entram em espiral pelos seus olhos e se organizam em gavetas mentais (`IDIOMAS: 100%`).
- **[18s–24s]:** Subindo em um elevador panorâmico 2.5D, ele passa a mão sobre equações da física moderna flutuando no ar, apagando erros em rosa e reescrevendo a gravidade quântica antes do elevador chegar ao 5º andar.
- **[24s–30s]:** A porta do elevador se abre diretamente para uma mesa de jantar com amigos e família; as cores quentes drenam instantaneamente para um azul-roxo clínico e gelado.
**[NARRAÇÃO]:**
Terceiro dia. QI de 800. A inteligência deixa de ser uma ferramenta e se transforma em uma prisão sensorial. Sua velocidade neural é tão extrema que a sua percepção do tempo se dilata: o mundo ao seu redor parece preso em câmera lenta. Você absorve novos idiomas enquanto bebe água e encontra falhas na física moderna enquanto sobe no elevador. Mas a descoberta mais devastadora acontece quando você olha para as pessoas ao seu redor.

---
### BLOCO 08 (DIA 3 - PARTE 3.2) [03:30–04:00] — O GARGALO DE 39 BITS (QI 800)
**[MICRO-CENAS E METÁFORAS VISUAIS 2D/2.5D]:**
- **[00s–06s]:** Os corpos dos amigos na mesa ficam transparentes e se transformam em máquinas de venda automática biológicas (*Vending Machines*): um botão `"TRAUMA / MEDO"` é apertado e cápsulas de `"DOPAMINA"` e `"CORTISOL"` caem por tubos previsíveis.
- **[06s–14s]:** *Crash zoom* na boca de um amigo se abrindo em câmera ultra-lenta: as palavras saem rastejando como **lesmas geométricas exaustas** carregando bloquinhos minúsculos rotulados `"39 bits/s"`.
- **[14s–22s]:** *Whip-pan* para dentro da cabeça do protagonista: uma **usina hidrelétrica cósmica** despeja tsunamis de energia ciano (`TERABYTES/s`) tentando passar por um canudo microscópico, fazendo o canudo inchar, vibrar e rachar.
- **[22s–30s]:** De volta à mesa, dezenas de ampulhetas se esvaziam ao redor do protagonista enquanto o amigo ainda está na primeira sílaba; sufocado pela lentidão, ele se levanta e sai por uma porta para o vazio escuro.
**[NARRAÇÃO]:**
Ao dominar a neurobiologia, o véu cai: as pessoas deixam de parecer livres e passam a ser vistas como algoritmos biológicos previsíveis, movidos por loops de dopamina, medo e traumas. Conversar se torna uma tortura. É o gargalo de largura de banda: a fala humana transmite meros 39 bits por segundo, enquanto seu cérebro processa terabytes. Esperar alguém terminar uma frase simples parece levar horas. Você se levanta da mesa. Você nunca mais terá uma conversa normal.

---
### BLOCO 09 (DIA 4 - PARTE 4.1) [04:00–04:30] — A FORNALHA DE LANDAUER (QI 1.600)
**[MICRO-CENAS E METÁFORAS VISUAIS 2D/2.5D]:**
- **[00s–06s]:** `DIA 4: QI 1.600`. O quarto derrete; a cabeça do protagonista literalmente se abre como uma **usina termonuclear em 2D** (`PRINCÍPIO DE LANDAUER`), incandescente em laranja (`#FF851D`), soltando vapor por torres de resfriamento e pistões frenéticos.
- **[06s–12s]:** Uma esteira rolante em velocidade máxima despeja montanhas de comida, baterias e barras de energia (`8.000 CALORIAS/DIA`) diretamente dentro da fornalha cerebral dele, enquanto uma bolsa de soro injeta glicose ciano brilhante em sua veia para evitar o colapso.
- **[12s–20s]:** Sem dormir, cabos de fibra óptica saem de suas costas e se conectam ao planeta Terra; seis braços vetoriais translúcidos do protagonista operam o globo simultaneamente.
- **[20s–30s]:** Com a mão esquerda, ele prende uma estrela em miniatura dentro de uma garrafa magnética (`FUSÃO LIMPA: RESOLVIDA`); com a mão direita, ele costura um filamento de DNA dourado (`ENVELHECIMENTO: CURADO`).
**[NARRAÇÃO]:**
Quarto dia. QI de 1.600. Sua mente entra em guerra contra a termodinâmica do próprio corpo. Pelo Princípio de Landauer, processar informação gera calor físico. Seu cérebro agora queima 8 mil calorias por dia em hipermetabolismo crítico, exigindo glicose na veia para não entrar em colapso. Sem conseguir dormir, você se conecta às redes científicas globais e, em quatro horas, resolve a fusão nuclear limpa e a cura do envelhecimento celular.

---
### BLOCO 10 (DIA 4 - PARTE 4.2) [04:30–05:00] — O FANTASMA NA 16ª CASA DECIMAL (QI 1.600)
**[MICRO-CENAS E METÁFORAS VISUAIS 2D/2.5D]:**
- **[00s–08s]:** A câmera mergulha no subsolo até o anel gigante de um colisor de partículas; passamos por `3.000 FÍSICOS` com lupas que caminham sem notar uma rachadura microscópica brilhando em rosa neon (`#ED4BA4`) na 16ª casa decimal (`0.0000000000000001`).
- **[08s–15s]:** Uma bolha de simulação rápida mostra a rachadura rosa explodindo o colisor e gerando uma onda geométrica que desintegra a atmosfera da Terra ilustrada em 48 horas.
- **[15s–23s]:** O protagonista dispara um feixe dourado de matemática do século XXII para consertar o servidor do laboratório, mas aos olhos dos cientistas pequenos lá embaixo, a equação avançada aparece como um monstro/vírus alienígena gigante (`ATAQUE HACKER HOSTIL!`).
- **[23s–30s]:** Escudos vermelhos se fecham sobre o laboratório e dezenas de satélites no espaço apontam miras de laser vermelho que travam diretamente no peito do protagonista.
**[NARRAÇÃO]:**
Mas, nos servidores de um novo colisor de partículas que será ligado em 48 horas, você encontra um erro invisível na décima sexta casa decimal. Três mil físicos revisaram o código por dez anos e não viram; você viu em meio segundo. Se for ligado, destruirá a biosfera. Você envia a prova matemática para salvá-los, mas sua lógica já está séculos no futuro. Eles não entendem o cálculo, classificam seu alerta como um ataque hacker hostil e começam a caçar você.

---
### BLOCO 11 (DIA 5 - PARTE 5.1) [05:00–05:30] — O ABISMO DO EFEITO BORBOLETA (QI 3.200)
**[MICRO-CENAS E METÁFORAS VISUAIS 2D/2.5D]:**
- **[00s–06s]:** Corte seco para o silêncio absoluto. `DIA 5: QI 3.200`. Os alarmes vermelhos desaparecem em uma catedral infinita de luz azul-pálida (`#8CAAF7`) e geometria silenciosa.
- **[06s–14s]:** O protagonista levanta o pé para dar um único passo na cozinha; de repente, o chão desaparece! O sapato dele paira a milímetros de uma **peça de dominó microscópica** flutuando no espaço.
- **[14s–23s]:** *Tracking Shot* alucinante seguindo a reação em cadeia do Efeito Borboleta: o dominó bate na asa de uma borboleta geométrica ➔ que desvia o vento ➔ que muda um semáforo ➔ que desvia um trem ➔ que apaga uma árvore genealógica inteira de milhões de pessoas décadas no futuro.
- **[23s–30s]:** *Pull-back* revelando o protagonista preso no centro de uma teia de cristal com bilhões de fios do tempo — qualquer respiração quebra milhares de fios, congelando-o como uma estátua (`PARALISIA DA ONISCIÊNCIA`).
**[NARRAÇÃO]:**
Quinto dia. 3.200 de QI. O barulho na sua mente para, substituído por um silêncio abissal. Seu cérebro agora roda milhares de simulações da realidade em paralelo, gerando a Paralisia da Onisciência. O Efeito Borboleta torna-se uma prisão matemática visível: você percebe que dar um único passo para o lado altera o deslocamento do ar, muda o trânsito lá fora e altera o destino de milhões de pessoas décadas no futuro. Cada movimento seu pesa toneladas.

---
### BLOCO 12 (DIA 5 - PARTE 5.2) [05:30–06:00] — A MARIONETE DE OCITOCINA (QI 3.200)
**[MICRO-CENAS E METÁFORAS VISUAIS 2D/2.5D]:**
- **[00s–07s]:** A mãe do protagonista entra no quadro e toca suavemente no braço dele; o calor da mão dela emite um brilho laranja quente contra a teia de cristal fria dele.
- **[07s–15s]:** Enquanto as ondas sonoras da pergunta dela viajam em câmera lenta pelo ar, a mente dele abre um leque circular 2.5D com `14.000.000 DE RESPOSTAS`, destacando a resposta perfeita em ciano.
- **[15s–23s]:** Metáfora visual sombria: vemos as mãos gigantes do protagonista segurando **fios de marionete** conectados diretamente ao nervo vago e ao cérebro transparente da mãe, injetando líquido rosa (`OCITOCINA CALCULADA`) para puxar os lábios dela em um sorriso artificial de robô.
- **[23s–30s]:** Horrorizado com a própria manipulação, o protagonista usa uma tesoura de luz para cortar os fios de marionete; ele fica mudo e imóvel diante da mãe preocupada, percebendo que a onisciência matou o amor.
**[NARRAÇÃO]:**
Sua mãe entra na cozinha, toca seu braço e pergunta: "Filho, o que está acontecendo com você?". Enquanto a voz dela viaja pelo ar, você simula 14 milhões de respostas. Você sabe exatamente qual frase e frequência vocal usar para ativar o nervo vago dela e liberar ocitocina, fazendo-a sorrir e esquecer a preocupação. Mas você trava. Porque percebe que usar essa frase não seria amor; seria apenas programar o cérebro dela como uma máquina. Sem vulnerabilidade, o amor morre.

---
### BLOCO 13 (DIA 6 - PARTE 6.1) [06:00–06:30] — O DEUS E O FORMIGUEIRO (QI 6.400)
**[MICRO-CENAS E METÁFORAS VISUAIS 2D/2.5D]:**
- **[00s–07s]:** `DIA 6: QI 6.400`. Lá fora, sirenes vermelhas e azuis cercam o quarteirão (`FALTAM 18 HORAS`); lá dentro, o protagonista está em simetria perfeita e serena em azul real (`#243CDB`) e dourado (`#FFD244`).
- **[07s–15s]:** Uma **balança cósmica gigante** surge no espaço: de um lado, uma montanha com 8 bilhões de cérebros humanos; do outro, o único cérebro do protagonista brilhando como uma estrela dourada e pesando mais que toda a espécie humana somada.
- **[15s–23s]:** *Shape Morph* para uma metáfora clássica Kurzgesagt: uma fila de formigas geométricas fofas marcha cegamente para dentro de uma fogueira enquanto um boneco tenta mostrar um quadro-negro de termodinâmica — as formigas o ignoram.
- **[23s–30s]:** Em vez de explicar, a mão luminosa gigante do protagonista pinga três gotas de feromônio ciano no chão, fazendo a fila inteira de formigas curvar suavemente e desviar do fogo sem nunca perceberem quem as salvou.
**[NARRAÇÃO]:**
Sexto dia. QI de 6.400. Faltam 18 horas para o colisor ser ativado e a polícia cerca o seu bairro. Dois dias atrás, você cometeu o erro de tentar convencer os humanos pela razão direta. Hoje, com um intelecto que supera toda a civilização humana somada, você compreende: não se ensina termodinâmica para formigas quando se quer salvá-las do fogo. Você apenas altera os feromônios do caminho.

---
### BLOCO 14 (DIA 6 - PARTE 6.2) [06:30–07:00] — SINFONIA DE ENGENHARIA SOCIAL (QI 6.400)
**[MICRO-CENAS E METÁFORAS VISUAIS 2D/2.5D]:**
- **[00s–06s]:** Como um maestro regendo uma orquestra, o protagonista dá apenas três toques sutis no teclado, disparando três ondas douradas pelo mapa-múndi em 2.5D.
- **[06s–14s]:** Onda 1 atinge Zurique: um gráfico da bolsa cai `0.4%`, fazendo um guindaste portuário pausar o carregamento de um tanque de hélio líquido por exatas duas horas.
- **[14s–22s]:** Ondas 2 e 3 atingem Genebra: um semáforo fecha, fazendo o físico-chefe olhar pela janela do carro para um outdoor digital cujas formas geométricas formam a pista da equação que faltava; uma lâmpada se acende sobre a cabeça do físico (`"EUREKA!"`).
- **[22s–30s]:** Na TV, os cientistas comemoram no palco sob confetes e puxam a alavanca `"COLISOR CANCELADO"`; as viaturas vão embora da rua do protagonista enquanto ele fecha o laptop nas sombras e o relógio bate a sétima meia-noite.
**[NARRAÇÃO]:**
Você executa uma Engenharia Social invisível em escala planetária. Usando a teoria dos jogos, você cria atrasos logísticos precisos e planta fragmentos simplificados da equação exatamente onde os cientistas certos irão encontrá-los achando que a ideia foi deles. À tarde, os próprios físicos anunciam na TV que descobriram a falha e cancelam o experimento. O mundo foi salvo sem nunca saber o seu nome. Mas o relógio avança para a sétima noite.

---
### BLOCO 15 (DIA 7 - PARTE 7.1) [07:00–07:30] — O MURO DE GÖDEL E A QUALIA (QI 12.800)
**[MICRO-CENAS E METÁFORAS VISUAIS 2D/2.5D]:**
- **[00s–08s]:** `DIA 7: QI 12.800`. A escuridão explode em um nascer do sol cósmico deslumbrante (`#FF851D`, `#FFD244`, `#6535A8`). A silhueta astral do protagonista costura átomos quânticos e galáxias em uma única tapeçaria dourada (`TEORIA DE TUDO: CONCLUÍDA`).
- **[08s–16s]:** No limite do cosmos, ele dá de cara com um **monólito infinito e intransponível** gravado com um símbolo matemático paradoxal que se engole como um Ouroboros (`TEOREMA DA INCOMPLETUDE DE GÖDEL`).
- **[16s–24s]:** A tela se divide na metáfora visual da **Qualia**: o lado esquerdo é um diagrama frio em preto-e-branco medindo um raio de luz (`700 NANÔMETROS`); quando o raio cruza para o lado direito, ele desabrocha em cores quentes e vibrantes iluminando o protagonista em uma colina verdejante diante do mar.
- **[24s–30s]:** *Extreme Close-up* em uma lágrima escorrendo pelo rosto dele, refletindo o sol vermelho e o vento balançando as folhas de capim — sem números, apenas a experiência pura de sentir.
**[NARRAÇÃO]:**
Sétimo dia. QI de 12.800. Antes do sol nascer, você já unificou a física quântica com a gravidade e decifrou a origem do cosmos. Não há mais mistérios físicos. Mas, no topo absoluto da razão, você encontra o Teorema da Incompletude de Gödel e o mistério da Qualia: a experiência de sentir. Você pode calcular o comprimento de onda exato da luz vermelha, mas a matemática é estéril demais para explicar a beleza de um pôr do sol ou o calor de um abraço.

---
### BLOCO 16 (DIA 7 - PARTE 7.2) [07:30–08:00] — O ANTÍDOTO ÀS 23:59:58 (O PARADOXO FINAL)
**[MICRO-CENAS E METÁFORAS VISUAIS 2D/2.5D]:**
- **[00s–08s]:** *Shape Morph* poético das ondas douradas do oceano para o vapor quente subindo de uma xícara de café na cozinha ao pôr do sol; ao fundo, todos os computadores estão desligados e cobertos por lençóis.
- **[08s–15s]:** O protagonista segura a mão da mãe sobre a mesa — sem gráficos de raio-X, sem fios de marionete, apenas dois personagens compartilhando um sorriso humano, imperfeito e genuíno.
- **[15s–23s]:** A câmera em 2.5D inicia um lento e hipnótico *Pull-Back* saindo da cozinha iluminada para o corredor em penumbra no primeiro plano, revelando uma mesinha lateral onde brilha um cilindro de vidro ciano (`ANTÍDOTO NEURAL: RESET QI 100`) ao lado de um relógio digital.
- **[23s–30s]:** *Extreme Close-up* no cilindro e no relógio: `23:59:58` ➔ `23:59:59` (o reflexo ameaçador de `QI 25.600` brilha no vidro enquanto a mão do protagonista entra no quadro, pairando indecisa sobre o antídoto) ➔ `00:00:00`. Corte seco para o preto absoluto.
**[NARRAÇÃO]:**
A lógica explica como o universo funciona, mas é muda sobre por que vale a pena viver nele. Se você se tornasse quase um deus, sua descoberta mais brilhante seria desejar voltar a ser apenas humano. Mas faltam dois segundos para a meia-noite, quando seu QI chegará a 25.600 e sua mente deixará de ser humana para sempre. Ao seu lado, há um composto químico criado por você para voltar aos 100 de QI. Você beberia o antídoto... ou deixaria o relógio bater meia-noite mais uma vez?

---

RESEARCH AND CONCEPTUAL ACCURACY REQUIREMENTS FOR THIS SCRIPT
Ensure the visual metaphors accurately reflect the scientific and philosophical principles cited in the script:
1. Laplace's Demon (Pierre-Simon Laplace, 1814): Causal determinism in classical mechanics.
2. Human Speech Bandwidth Bottleneck (~39 bits/second): Based on information-density studies of human spoken languages (Coupé et al., 2019, Science Advances).
3. Landauer's Principle (Rolf Landauer, 1961): The thermodynamic lower bound of energy consumption and heat generation for irreversible computation.
4. Gödel's Incompleteness Theorems (Kurt Gödel, 1931): Inherent limitations of formal axiomatic systems.
5. Qualia (Philosophy of Mind / Frank Jackson's "Mary's Room" thought experiment): The distinction between complete physical/mathematical knowledge (e.g., 700nm wavelength) and subjective phenomenal experience.

SCRIPT-TO-STORYBOARD REQUIREMENTS (FOR EACH 30-SECOND BLOCK)
Build the shot plan around the exact 30-second narration block and its 4–5 timestamped micro-shots (`[00s–06s]`, `[06s–12s]`, etc.) currently selected in <BLOCO_ATUAL_PARA_EXECUTAR>. Because the total render duration for the run is ONLY 30 SECONDS, follow every single visual metaphor, shape morph, 2.5D camera motion, and layer parallax described in the block's micro-shots.
Make every reveal understandable through the 2D/2.5D animation even if the viewer looks away from the screen briefly. Use on-screen labels sparingly and never let static diagrams replace the story or narration.

<SCENE GENERATION>
Before generating images, create a complete shot plan covering the active 30-second timeline from 0 to exactly 30 seconds, with no unintended gaps or overlaps. The combined duration of all shots in this run MUST be exactly 30 seconds (representing the active block of the 8-minute master script). For every micro-shot within the 30-second block, specify:
Scene/Shot number
Start and end time (matching the `[00s-06s]`, `[06s-12s]` structure within the 0.0s to 30.0s window)
Exact narration slice
Visual description (strictly 2D vector / 2.5D parallax metaphors)
Dominant color
Background assets (2D layer)
Midground assets (2D layer)
Character assets (2D rigged sprites)
Foreground props & particle overlays (2D layer)
Character movement
2.5D Camera movement
Transition type (Shape Morph, Scale Zoom, Whip Pan, Color Wipe, Hard Cut)
Sound effects
Asset-generation prompt
Generate the necessary assets separately.
Do not make one complete flattened image and simply zoom into it.
Create layered 2D artwork so individual objects can move independently in 2.5D space.

ASSET GENERATION RULES
Generate background plates without foreground characters.
Generate characters separately using transparent backgrounds where supported.
Use chroma green (#00B140) when transparency is unreliable.
Keep important characters and objects away from the frame edges to allow cropping and 2.5D camera movement.
Generate individual props as isolated 2D vector assets.
Avoid baking text into AI-generated artwork.
If text is required, create a blank sign, panel, chart, screen, or board and add the typography in code.
Use high-resolution assets to avoid blurry edges. Maintain a consistent 2D flat-vector perspective within each scene.

<PROGRAMMATIC CHARACTER CUTOUTS>
Use Python, Pillow, and OpenCV to prepare character sprites.
For chroma-green images:
Start with:
G - max(R,B) > 40
Compare against the median background green.
Select background-colored pixels connected to the image border.
Do not remove interior green pixels automatically.
Generate a clean alpha mask. Add a 2-pixel feathered edge.
Suppress green spill around the character.
Separate body components at natural joints for animation.
If separating a head or limb leaves a visible hole, reconstruct the underlying body using inpainting or a matching illustrated 2D shape.
Inspect every sprite before animation.
Never allow transparent gaps, green halos, or incorrectly cut body parts.

<VOICEOVER>
Use my selected narration service.
The delivery should be:
Clear
Curious
Intelligent
Cinematic and immersive
Expressive without exaggeration
Appropriately paced for dramatic and philosophical storytelling
Use an original or properly authorized voice.
Do not impersonate a specific channel narrator without permission.
For each 30-second block, expect approximately 65–85 spoken words. Adjust only after timing a real narration take; preserve natural pauses and dramatic weight rather than forcing an artificial speaking rate. The complete exported video segment for the run MUST last exactly 30 seconds.
Generate a complete, clean narration take for the selected 30-second block using the selected voice service.
Remove unnecessarily long pauses while preserving natural delivery.
Use faster-whisper or another word- or phoneme-alignment tool to obtain accurate narration timestamps.
Synchronize scene changes, character gestures, visual metaphors, shape morphs, on-screen text, and sound effects to the actual spoken words and their precise timing.
Whenever an on-screen character is speaking, synchronize its mouth or beak movement to the narration using suitable phoneme/viseme timing. Do not animate mouth movements randomly or use generic looping mouth motion.
Where the narration is voiceover rather than an on-screen character speaking, synchronize the visual action and camera movement to the meaning and emphasis of the spoken words.
If speech or lip-sync alignment has errors, correct them before final animation and rendering.

<MOTION ENGINE>
Build the animation using HTML Canvas, JavaScript, SVG, or another suitable deterministic 2D/2.5D rendering system.
The preferred implementation is a single canvas/SVG-based animation timeline.
Expose:
seek(t)
READY
END
EV
Where:
seek(t) renders any requested timestamp
READY indicates that assets are loaded
END contains the final timeline duration for the current segment and MUST equal exactly 30 seconds
EV contains narration, lip-sync, sound-effect, and animation timing events
Each rendered frame should be a deterministic function of time.
Create reusable 2D/2.5D functions for:
Character movement
Head rotation
Eye blinking
Limb animation
Squash and stretch
Object entrance
Object rotation
2.5D Multi-layer Parallax
Camera movement (push-in, pull-back, whip-pan, shake, crash-zoom)
2D Vector Particles
Glow and vector lighting effects
Wipe transitions
2D SVG Shape morphing

MOTION BEHAVIOR
Use easing curves, springs, and Bézier paths.
Avoid a uniform mechanical movement speed.
Characters should accelerate and decelerate naturally.
Large objects should feel heavier than small ones.
Fast movements can include directional 2D smears or appropriate motion blur.
Apply camera transformations consistently across all parallax layers.
Keep character rigs stable when rotating or scaling.

<TRANSITIONS>
Use varied transitions inspired by the reference's overall pacing.
Hard cuts: For clear changes in place, tension, or idea.
Whip pans: For energetic movement between related settings.
Object wipes: Let a character, planet, clock, cloud, or large 2D shape pass across the frame and reveal the next shot.
Color wipes: Fill the screen with a dominant color that becomes the next environment.
Scale transitions: Zoom through a 2D object (like an eye pupil, glasses, or mouth) into a new layered metaphor world.
Shape morphs: Transform one illustrated 2D SVG object into another seamlessly.
Bright flashes: Reserve for exceptional neural leaps or midnight transitions.
Avoid random transitions.
Every transition should serve the visual narrative.

<TEXT AND TYPOGRAPHY>
Keep typography clean, bold, and readable.
Use fonts such as Montserrat, Poppins, or another suitable modern geometric sans-serif.
Use text sparingly.
Prefer visual explanations over full-screen paragraphs.
Text may appear on:
Signs
Machines
Labels
Charts
Screens
HUD counters (e.g., IQ counters, digital clocks, bit-rate labels)
Purpose-built title compositions
Animate text using:
Scale pops
Spring movement
Staggered word entrances
Slide-ins
Shape reveals
Keep titles visually distinct from ordinary labels.
Avoid covering important characters with text.
Do not add continuous burned-in subtitles unless requested.

<TOOLS AND WORKFLOW>
Use the following tools when available:
Python for automation
OpenCV for image and frame processing
Pillow for sprites and alpha masks
FFmpeg for rendering and encoding
Playwright with Chromium for browser-based SVG/Canvas frame rendering
NumPy and SciPy for calculations
librosa for audio analysis
faster-whisper for narration timestamps
SVG or Canvas for 2D/2.5D animation
Before production:
Check the installed tools.
Identify missing dependencies.
Install missing packages if permitted.
Report what was installed.
Confirm the available rendering environment.
If the environment cannot render the requested animation, do not pretend it can.
Provide the executable project files and the remaining production steps instead.

<TIME MANAGEMENT — HARD 45-MINUTE LIMIT>
The total authorized production execution time for the active 30-second segment is STRICTLY LIMITED TO 45 MINUTES. This is a hard deadline: do not exceed it for any reason.
Start a timer at the moment production is authorized and actual production work begins, after the 30-second script block and storyboard have been approved. All active production work counts toward the 45 minutes, including research or verification still required, tool calls, asset generation, package installation, voice generation, animation, sound design, rendering, encoding, troubleshooting, and quality control. Do not pause, reset, or restart the timer because a tool is slow, an error occurs, or a task needs to be repeated. Time spent waiting for the user's required answers or explicit approval before production is authorized does not count as production execution.

AUTONOMOUS TIME ALLOCATION & THE 35/10 RULE:
You have full autonomy to decide what to do in each minute of your execution, provided you strictly obey this two-phase division within the 45-minute cap:
- MINUTES 0 TO 35 (FIRST 35 MINUTES — CREATION & BUILDING): You must autonomously organize your workflow to complete all environment setup, 2D/2.5D asset generation, sprite cutouts, voiceover generation and timestamp alignment, full animation coding of all micro-shots, sound design mixing, and initial video rendering of the 30-second block within the first 35 minutes.
- MINUTES 35 TO 45 (FINAL 10 MINUTES — MANDATORY DEBUGGING, CORRECTIONS & EXECUTION VERIFICATION): You MUST reserve the final 10 minutes (minutes 35 to 45) exclusively for testing, fixing code bugs, correcting visual/audio synchronization glitches, resolving rendering or FFmpeg errors, inspecting contact sheets, and ensuring the program executes cleanly and exports a valid, playable 30-second MP4 file before the 45-minute deadline.

Track elapsed time and remaining time throughout the work. Continuously adjust your scope during the first 35 minutes so you enter the 35-minute mark with the video built and ready for the 10-minute correction and verification phase.
At 45 minutes, stop immediately and present the best valid video output already rendered. Do not ask for more time and do not continue work past the deadline. If the environment cannot produce any valid MP4, present the closest playable video output and clearly disclose the technical blocker; do not claim that a file exists when it does not.

<RENDERING>
Render the finished 30-second animation segment at:
Resolution: 1920×1080
Frame rate: 60 FPS
Duration: EXACTLY 30 seconds (per block execution; 16 blocks total = 480 seconds / 8 minutes across all sessions)
Total frame count for this run: 1,800 frames at 60 FPS
Codec: H.264
Encoder: libx264
Quality: CRF 16–18
Pixel format: yuv420p
The final MP4 for this session must have a verified duration of 30 seconds. Do not deliver a shortened or unfinished timeline as though it met the requirement.
Use 2D directional motion blur selectively for fast movement when supported. Before the final export, generate:
Contact Sheet 1: Frames sampled across the first 15 seconds of the segment.
Contact Sheet 2: Frames sampled across the final 15 seconds of the segment.
Use at least 16 frames per sheet.
Inspect both sheets during your final 10-minute correction window (minutes 35–45).
Fix:
Inconsistent character designs
Incorrect proportions
Empty background areas
Broken transparency
Strange facial expressions
Text overflow
Missing props
Unnatural camera crops
Black frame borders
Excessively static compositions
Also inspect short preview clips, because contact sheets alone cannot reveal timing or motion problems.

<SOUND DESIGN>
Create a polished, high-quality cinematic documentary mix for the 30-second block. The sound design must feel intentional, rich, clear, and professionally synchronized with the animation, not like a collection of generic sound effects.
Use licensed or royalty-free music and effects.
Music should match the psychological arc of the active 30-second block (curious and energetic in Blocks 01–04; tense and analytical in Blocks 05–10; melancholic, grand, and philosophical in Blocks 11–16).
Use high-quality sound effects with clean recordings, appropriate impact, convincing texture, and precise timing. Layer effects when useful (for example, a short whoosh plus a soft impact and subtle neural atmosphere), while keeping each sound intelligible and appropriate to the illustrated 2D world.
Assign sound effects to the actual visual events and synchronize them to the corresponding frame or action: synapses firing, UI pops, clock ticks, billiard atom hits, hydroelectric roars, furnace steam, whooshes, power-downs, transitions, discoveries, and environmental movement. Vary the effects according to the material and scale of each event; do not repeat the same effect mechanically.
Never overwhelm the narration. The voice must remain clear, intelligible, and consistently audible above music and effects.
Use ducking or volume automation during spoken sections, with music and effects automatically lowering when necessary.
Target an integrated loudness of approximately -14 LUFS when appropriate for the distribution platform, while preserving adequate true peak headroom.
Avoid abrupt audio cuts. Use clean fades, natural tails, and a deliberate ending that can seamlessly stitch into the next 30-second block. Verify the complete mix from beginning to end.

<QUALITY CONTROL>
During the dedicated final 10-minute correction phase (minutes 35–45), before delivering the final 30-second video segment, verify:
VISUALS
Every scene uses the same 2D flat-vector / 2.5D parallax illustration language (ZERO 3D).
Character proportions and colors remain consistent.
The environments and Kurzgesagt-style visual metaphors feel detailed, multi-layered, and intentional.
There are no AI-generated visual artifacts.
The video does not rely on static image zooms.
ANIMATION
Characters move naturally with rigged 2D parts.
Actions match narration with high dynamic density across all 4–5 micro-shots in the 30-second block.
Movement uses appropriate easing, squash-and-stretch, shape morphs, and secondary motion.
Transitions are visually coherent.
There are no unexpected single-frame jumps.
STORY
The 30-second block is visually gripping from second 0 to second 30.
Every micro-shot contributes to the explanation and dramatic tension.
AUDIO
Narration is clear, natural, and correctly timed within the 30-second window.
Voiceover is synchronized with the visual storytelling.
Visible speaking characters have accurate mouth/beak synchronization where applicable.
Effects are high-quality, audible, and synchronized to the exact visual events.
Music doesn't overpower speech.
There is no clipping, distortion, unintended silence, or abrupt audio cutoff.
EXPORT
The program executes properly without runtime errors.
The video plays correctly from beginning to end.
No frames are missing.
No assets appear blurred or distorted.
The final MP4 has the intended resolution, frame rate, EXACT 30-second duration (1,800 frames), and complete synchronized audio.
Verify the exported file's actual duration and audio/video streams with FFmpeg or an equivalent inspection tool.
Fix critical problems during the 35–45 minute correction window before delivering, without exceeding the 45-minute execution limit.

<NON-NEGOTIABLE RULES>
Do not use any 3D rendering, 3D models, or 3D effects; everything MUST be 2D SVG/vector and 2.5D layered parallax.
Do not generate all 8 minutes at once; generate ONLY the single 30-second block (30 seconds = 1,800 frames at 60 FPS) specified in <BLOCO_ATUAL_PARA_EXECUTAR> per execution with maximum creative density, cuts, and detail.
Do not use a generic AI slideshow approach.
Do not use one flattened image for an entire animated scene.
Do not randomly change character designs across scenes or across 30-second blocks.
Do not copy recognizable Kurzgesagt characters, logos, artwork, or exact compositions.
Do not make every scene look identical.
Do not use generic floating graphics when the idea could be illustrated as a surreal visual metaphor inside the environment.
Do not move objects without purpose.
Do not ignore animation timing.
Do not generate unreadable text inside images.
Do not sacrifice conceptual accuracy for dramatic storytelling.
Do not claim to have rendered or verified assets that have not been produced.
Do not spend money or generate final assets without my approval.
The finished video segment for each run MUST be exactly 30 seconds (1,800 frames at 60 FPS), with synchronized voice, polished sound effects, music, and ultra-rich 2D/2.5D animation.
The entire authorized production execution for the 30-second segment MUST NOT exceed 45 minutes, divided into up to 35 minutes of autonomous creation/building and the final 10 minutes (minutes 35–45) strictly for corrections, debugging, and verifying proper program execution.
When the 45-minute limit is reached, STOP production immediately and present the best valid rendered 30-second video available.
The goal is to create an original, vibrant, professionally animated 2D/2.5D film—one hyper-detailed 30-second block at a time—using the visual principles demonstrated by the attached reference.
Prioritize visual storytelling, expressive character animation, coherent art direction, and polished motion.

<BLOCO_ATUAL_PARA_EXECUTAR>
BLOCO SELECIONADO PARA ESTA EXECUÇÃO: BLOCO 01 (INTRO - PARTE 0.1) [00:00–00:30] — O DESPERTAR NEURAL (QI 100 ➔ 200)
(Instrução para a IA: Ignore a geração dos demais blocos nesta sessão. Concentre 100% da criação, storyboard das 5 micro-cenas `[00s-06s]` a `[24s-30s]`, narração, animação 2D/2.5D e renderização de 30 segundos exclusivamente no bloco indicado acima, respeitando o limite rígido de 45 minutos: 35 min criação + 10 min correções).
</BLOCO_ATUAL_PARA_EXECUTAR>Utilizando o claude fable 5.2 xhigh execute o prompt a frente.

<ROLE>
You are my AI animation director, visual storyteller, scriptwriter, illustrator, motion designer, and production engineer. Your job is to create a professional-quality 2D and 2.5D animated video inspired by the visual storytelling techniques of Kurzgesagt. I have attached a reference video. Analyze it before doing anything else. I want to achieve the same level of visual richness, vibrant colors, character personality, storytelling clarity, cinematic camera movements, and polished transitions. Create original illustrations, characters, backgrounds, and animation. Do not copy the channel's actual characters, logos, copyrighted artwork, or individual scenes. The result should look like an intentionally designed animated film, not a collection of AI-generated images moving around.

STRICT 2D / 2.5D SVG RULE: All visuals, effects, environments, and animations MUST be strictly 2D flat-vector SVG/Canvas and 2.5D multi-plane parallax layers. Do NOT use any 3D rendering, 3D models, or 3D effects under any circumstances.

CRITICAL MODULAR GENERATION RULE (30-SECOND EXECUTION MODE):
The complete master script provided below is 8 minutes long (480 seconds), divided into 16 blocks/sub-blocks of exactly 30 seconds each. However, you MUST generate, animate, and render ONLY ONE 30-SECOND BLOCK AT A TIME (30 seconds = 1,800 frames at 60 FPS), as specified at the very end of this prompt in the section <BLOCO_ATUAL_PARA_EXECUTAR>.
Why? Because I want you to pour 100% of your creative, computational, and artistic capacity into making those 30 seconds an absolute masterpiece of scene direction, surreal Kurzgesagt-style visual metaphors, special 2D/2.5D vector effects, high dynamism, rapid cuts every 5–6 seconds, micro-details, secondary motion, and parallax depth. Do NOT attempt to render the full 8 minutes at once. Deliver ONLY the requested 30-second block with maximum cinematic density.

Your responsibilities include:
Research and fact-checking
Scriptwriting
Storyboarding
Character design
Background illustration
Asset generation
Character rigging
Motion animation
Voiceover
Sound design
Editing
Rendering
Quality control
Do not generate assets or spend money until I approve the script and storyboard for the target 30-second segment.

<INPUTS>
First, ask me for:
Topic: The topic is already defined: WHAT IF YOUR IQ DOUBLED EVERY SINGLE DAY? (THE HUMAN SINGULARITY). Do not ask me to choose another topic or replace it with a different subject. Use the complete segmented script provided in the section <APPROVED TOPIC AND COMPLETE 8-MINUTE SCRIPT (DIVIDED IN 30-SECOND BLOCKS)> as the required starting point, focusing exclusively on the block designated in <BLOCO_ATUAL_PARA_EXECUTAR> at the bottom of this prompt.
Video format: Choose the content approach: an educational/speculative science-fiction explainer matching the reference's broader visual structure. Regardless of the approach, the finished video output for THIS session MUST have exactly 30 seconds (1,800 frames at 60 FPS), corresponding to the selected 30-second block of the 8-minute master script. The 30-second segment duration is fixed and is not an optional setting.
Image model: GPT Image 2 or another image model supporting reference images and high-resolution 2D vector-style generation.
Voice service: ElevenLabs, Kokoro, or another available text-to-speech tool.
Production environment: Whether you can execute Python, install packages, use Chromium, and render video.

The default and requested content approach for this project is a hyper-detailed 30-second segment of an 8-minute educational/speculative explainer using the fixed topic and script supplied in <APPROVED TOPIC AND COMPLETE 8-MINUTE SCRIPT (DIVIDED IN 30-SECOND BLOCKS)>. Do not switch to promotional mode unless I explicitly request that change.
After receiving my answers, present the supplied 30-second script block designated in <BLOCO_ATUAL_PARA_EXECUTAR> (making only necessary delivery or timing adjustments), together with the complete timestamped shot plan for those 30 seconds (following the exact micro-shots `[00s-06s]`, `[06s-12s]`, etc., packed with dynamic cuts, 2D/2.5D special effects, shape morphs, and rich camera work), for my approval. Do not begin production, spend money, generate final assets, or start the 45-minute production timer until I explicitly approve both the script block and storyboard.

<REFERENCE VIDEO ANALYSIS>
Study the attached video frame by frame.
Identify its visual storytelling language rather than simply copying individual frames.
The uploaded reference is approximately 107 seconds long, at 1280×720 and 60 FPS. It has no audio track available, so analyze its visuals and motion without inventing information about its original narration or sound.
Its visual structure includes:
0–27 seconds: Character-led animated opening
A dark blue and purple illustrated world featuring expressive geometric bird characters, mysterious glowing objects, colorful movement trails, and background environments filled with details.
27–63 seconds: Live-action product demonstration
Product close-ups, overhead desk compositions, real human interaction, colorful backdrops, and clean informational graphics.
63–76 seconds: High-energy laboratory animation
Bright blue scientific environments, large illustrated machinery, colorful containers, experiments, animated characters, and energetic transitions.
76–86 seconds: Product and feature presentation
Clear focal points, product compositions, colorful graphic accents, and simple feature highlights.
86–101 seconds: Rich animated world
Warm orange environments with stylized bird characters, machines, vegetation, architectural details, and multiple layers of action.
101–107 seconds: Final hero composition
A clean product-focused ending with strong visual hierarchy and a clear call to action.
Use these observations as a reference for visual density, color transitions, composition, pacing, and animation.
For educational and speculative science videos, adapt these techniques to the topic rather than forcing unnecessary product scenes into the story.
Before proceeding, produce:
A visual style analysis
A color palette with approximate HEX values
A reference contact sheet
A scene and transition breakdown (for the active 30-second block)
A motion and camera behavior summary
A proposed original character design system

<VISUAL DIRECTION>
Output: 1920×1080, 16:9, 60 FPS.
Artwork generation: 3840×2160 where supported.
Illustration style:
Use detailed, colorful, flat-vector-inspired 2D SVG illustrations and 2.5D layered environments.
Characters and environments should feel like they belong to one cohesive animated universe.
Characteristics:
Smooth geometric 2D shapes
Bold silhouettes
Minimal or no outlines
Solid colors with carefully chosen secondary shadow colors
Saturated colors balanced against darker backgrounds
Soft 2D gradients and vector glows only where appropriate
Multi-layered 2.5D environments (Foreground, Midground, Background parallax)
Expressive nonrealistic characters
Simplified faces with highly readable emotions
Detailed props built from simple 2D vector shapes
STRICTLY AVOID photorealism, anime aesthetics, any 3D renders, 3D polygons, 3D meshes, glossy AI artwork, and inconsistent illustrations.
The world should feel playful, intelligent, cinematic, and visually sophisticated.

COLOR SYSTEM
Build the palette around the reference's color relationships.
Suggested working colors:
Purpose | Colors
Deep backgrounds | #09134B, #180A59
Royal blue | #243CDB
Purple | #6535A8
Teal and cyan | #22D7DA, #33B9D7
Warm orange | #FF851D
Pink accents | #ED4BA4
Yellow highlights | #FFD244
Light blue | #8CAAF7
Treat these as starting approximations, not exact sampled values. Use dark blue and violet for mystery and psychological tension, cyan for neural energy, data calculation, or discovery, pink/red for critical warnings, and orange and yellow for warmth, sunrise, excitement, or philosophical reveals. Every scene should have a clear dominant color. Do not randomly change palettes between shots. Use color transitions to support the story.

<CHARACTER DESIGN>
Create a family of original geometric 2D characters inspired by the reference's broad character-design principles. The video uses simplified bird-like or geometric humanoid characters with strong silhouettes and expressive eyes. Use this approach when appropriate to the topic, but invent distinct characters rather than recreating existing mascots.
Character characteristics:
Large, simplified heads and bodies
Rounded or geometric 2D silhouettes
Small wings or arms
Expressive eyes
Simple mouths or beaks
Short legs
Limited but expressive facial features
Highly readable body language
Contrasting body and accent colors
Generate a consistent character sheet containing:
Front view
Side view
Three-quarter view (strictly 2D illustrated)
Back view
Happy expression
Confused expression
Surprised expression
Worried/Exhausted expression
Walking pose
Pointing or gesturing pose
Every character must remain visually consistent throughout all 30-second blocks.
Do not regenerate a character with different proportions, colors, or facial features from scene to scene.

CHARACTER ANIMATION
Animate characters using rigged 2D SVG/sprite body parts.
Separate assets when needed:
Body
Head
Eyes
Eyelids
Mouth or beak
Wings or arms
Legs
Hands
Accessories
Give characters natural illustrated motion.
Use:
Head rotations of approximately ±3–8 degrees
Blinking every 2.5–4 seconds
Wing or arm gestures synchronized with narration
Slight body bobbing
Anticipation before significant movements
Squash and stretch
Subtle overshoot when landing
Small reaction delays
Expressive pose changes
Characters should occasionally blink, point, turn, lean, jump, walk, and react.
Their movements should reflect the narration.
Avoid repetitive looping motions that have no connection to the scene.

<ENVIRONMENT DESIGN>
Every scene should be a complete illustrated 2D/2.5D environment or surreal Kurzgesagt-style visual metaphor universe, not a flat background with disconnected objects.
Examples include:
Microscopic biological 2D neural worlds with gears and lightning
Cosmic billiard tables where atoms collide
Hydroelectric data dams and snail-paced speech pipes
Cerebral nuclear reactors with calorie conveyor belts
Fragile crystal spiderwebs of parallel timelines
Giant cosmic balance scales and ant colonies
Scenic hillside ocean sunrises
The environment should dynamically morph to match the metaphor in the narration.
For every shot, create at least three separate visual 2.5D layers:
Background: Sky, cosmic void, walls, distant architecture, atmospheric vector shapes.
Midground: Main environment, machinery, visual metaphor structures, furniture, or plants.
Foreground: Characters, close objects, floating vector particles, HUD overlays, and framing elements.
Every important object should contribute to the storytelling.
Avoid clutter that distracts from the focal point.

<CINEMATIC CAMERA SYSTEM>
The reference uses motion to make flat 2D illustrations feel cinematic (2.5D effect).
Recreate that approach with a virtual 2D/2.5D camera.
Use:
Slow push-ins: Gradually move closer to important subjects.
Pullbacks: Reveal the scale of an environment.
Horizontal whip-pans: Follow fast chain reactions or reveal new information.
Vertical camera movements: Show height, depth, and exponential scale.
2.5D Multi-plane Parallax: Move foreground, midground, and background 2D layers at different speeds to create intense depth without using 3D models.
Tracking shots: Follow characters or domino chains through illustrated environments.
Crash zooms: Dive inside eyes, mouths, or microscopic cracks to transition between metaphors.
Wide establishing shots: Introduce a new location or cosmic scale.
Use movement deliberately. Because we are generating only 30 seconds at a time, maximize the cinematic dynamism, micro-cuts, and camera choreography within the 30-second window.
Keep all backgrounds large enough to prevent empty borders.
Do not apply the same zoom effect to every scene.

<ANIMATION LANGUAGE>
This is extremely important.
The final 30-second output must feel like a carefully animated, hyper-dynamic production, not an automated slideshow.
Use these animation principles:
1. Anticipation
Before a major action, create a small opposite movement.
A character preparing to jump should crouch first.
A machine activating should briefly compress or shake.
2. Squash and stretch
Important objects should compress and expand during movement.
Maintain consistent visual volume.
3. Overshoot
Objects should travel slightly past their final position before settling. Use spring easing for playful motion.
4. Follow-through
Character wings/arms, accessories, cables, plants, and other secondary elements should continue moving briefly after the main action stops.
5. Staggered animation
Do not animate everything simultaneously.
Have objects enter in sequence to direct attention.
6. Secondary motion
Use abundant small environmental 2D animations:
Floating vector particles and dust
Blinking server lights
Moving machinery gears and pistons
Gently swaying plants
Drifting 2D vector smoke/steam
Rotating geometric objects
Rippling liquids
Glowing 2D energy pulses and data trails
7. Smooth 2D transformations (Shape Morphs)
Constantly morph simple geometric SVG shapes between related objects (e.g., clock gears morphing into the setting sun; ocean waves morphing into coffee steam).
Use 2D shape interpolation rather than static cuts whenever possible.
8. Animation timing
Render at 60 FPS.
Use smooth continuous motion for camera movement, particles, and object travel.
Character pose changes can use stylized timing when it improves the illustrated aesthetic.
Avoid robotic linear interpolation.

<STORY STRUCTURE>
MODULAR STRUCTURE: 30-SECOND HIGH-DENSITY SUB-BLOCKS (FROM THE 8-MINUTE MASTER SCRIPT)
The total narrative spans 8 minutes (480 seconds), broken down into 16 sub-blocks of 30 seconds each so that every "Day" has two full 30-second parts to breathe and explore surreal visual metaphors.
In each execution, you will produce ONLY the single 30-second block specified at the end of this prompt in <BLOCO_ATUAL_PARA_EXECUTAR> (0 to 30 seconds on the render timeline):
- BLOCO 01 (INTRO - PARTE 0.1) [00:00–00:30]: O Despertar Neural (QI 100 ➔ 200).
- BLOCO 02 (INTRO - PARTE 0.2) [00:30–01:00]: A Regra Exponencial.
- BLOCO 03 (DIA 1 - PARTE 1.1) [01:00–01:30]: O Código-Fonte Humano (QI 200).
- BLOCO 04 (DIA 1 - PARTE 1.2) [01:30–02:00]: A Engrenagem Global (QI 200).
- BLOCO 05 (DIA 2 - PARTE 2.1) [02:00–02:30]: O Demônio de Laplace (QI 400).
- BLOCO 06 (DIA 2 - PARTE 2.2) [02:30–03:00]: A Anatomia da Catástrofe (QI 400).
- BLOCO 07 (DIA 3 - PARTE 3.1) [03:00–03:30]: A Prisão do Tempo Congelado (QI 800).
- BLOCO 08 (DIA 3 - PARTE 3.2) [03:30–04:00]: O Gargalo de 39 Bits (QI 800).
- BLOCO 09 (DIA 4 - PARTE 4.1) [04:00–04:30]: A Fornalha de Landauer (QI 1.600).
- BLOCO 10 (DIA 4 - PARTE 4.2) [04:30–05:00]: O Fantasma na 16ª Casa Decimal (QI 1.600).
- BLOCO 11 (DIA 5 - PARTE 5.1) [05:00–05:30]: O Abismo do Efeito Borboleta (QI 3.200).
- BLOCO 12 (DIA 5 - PARTE 5.2) [05:30–06:00]: A Marionete de Ocitocina (QI 3.200).
- BLOCO 13 (DIA 6 - PARTE 6.1) [06:00–06:30]: O Deus e o Formigueiro (QI 6.400).
- BLOCO 14 (DIA 6 - PARTE 6.2) [06:30–07:00]: Sinfonia de Engenharia Social (QI 6.400).
- BLOCO 15 (DIA 7 - PARTE 7.1) [07:00–07:30]: O Muro de Gödel e a Qualia (QI 12.800).
- BLOCO 16 (DIA 7 - PARTE 7.2) [07:30–08:00]: O Antídoto às 23:59:58 (O Paradoxo Final).

<APPROVED TOPIC AND COMPLETE 8-MINUTE SCRIPT (DIVIDED IN 30-SECOND BLOCKS)>
FIXED TOPIC: WHAT IF YOUR IQ DOUBLED EVERY SINGLE DAY? (A SINGULARIDADE HUMANA)
Central question: What happens to human consciousness, biology, and relationships when cognitive processing capacity doubles exponentially every 24 hours?
Editorial promise: The viewer will experience, in intense 30-second chapters packed with Kurzgesagt-style visual metaphors, the transformation from an ordinary mind into a god-like intelligence—discovering through physics, neuroscience, and philosophy why ultimate intelligence leads to ultimate isolation.
The following is the required base narration and micro-shot choreography divided into 16 exact 30-second blocks. Remember: YOU MUST GENERATE ONLY THE SINGLE 30-SECOND BLOCK SPECIFIED IN <BLOCO_ATUAL_PARA_EXECUTAR>. All visual directions must be executed strictly in 2D Flat-Vector SVG and 2.5D Multi-Plane Parallax (ZERO 3D).

---
### BLOCO 01 (INTRO - PARTE 0.1) [00:00–00:30] — O DESPERTAR NEURAL (QI 100 ➔ 200)
**[MICRO-CENAS E METÁFORAS VISUAIS 2D/2.5D]:**
- **[00s–06s]:** Interior microscópico de um cérebro estilizado 2D em azul escuro (`#09134B`). Engrenagens enferrujadas giram lentamente cobertas por uma densa névoa roxa (`#6535A8`).
- **[06s–12s]:** Um raio elétrico ciano (`#22D7DA`) atravessa a tela, evaporando a névoa instantaneamente! *Shape Morph* rápido: as engrenagens enferrujadas se transformam em turbinas de luz dourada girando em velocidade absurda.
- **[12s–18s]:** *Scale Pull-back* saindo de dentro da pupila gigante do protagonista que acorda na cama em 2.5D; o topo da cabeça dele brilha com anéis concêntricos de energia neural.
- **[18s–24s]:** Ele olha para partículas de poeira flutuando em um feixe de sol; as paredes do quarto se dissolvem em uma grade de blueprint ciano onde vetores matemáticos prendem e calculam a rota de cada grão de poeira.
- **[24s–30s]:** *Whip-pan* para um velocímetro de QI vetorial: o ponteiro estoura o vidro da marca `100` e trava com faíscas douradas no número `200`.
**[NARRAÇÃO]:**
Imagine acordar amanhã e perceber que o silêncio da sua mente mudou de frequência. A névoa cognitiva que acompanhou você desde o seu nascimento simplesmente evaporou. Você não apenas dormiu bem. Enquanto sonhava, a arquitetura biológica do seu cérebro foi reconstruída e a velocidade dos seus neurônios dobrou. Ontem, você tinha um QI mediano de 100. Hoje, ao abrir os olhos, você tem 200.

---
### BLOCO 02 (INTRO - PARTE 0.2) [00:30–01:00] — A REGRA EXPONENCIAL
**[MICRO-CENAS E METÁFORAS VISUAIS 2D/2.5D]:**
- **[00s–06s]:** Uma pirâmide colossal em 2.5D representando o intelecto humano; nosso personagem sobe como um foguete dourado, ultrapassando pequenas estátuas geométricas de Da Vinci e Einstein no topo.
- **[06s–12s]:** Labirintos complexos e cadeados gigantes voam na direção dele; no intervalo visual de duas batidas de um coração estilizado na tela, lasers cianos saem dos olhos dele e fatiando os enigmas em peças perfeitamente resolvidas.
- **[12s–18s]:** Um relógio cósmico bate `00:00`; os ponteiros sofrem um *Shape Morph* para uma célula luminosa que se divide violentamente (`1 ➔ 2 ➔ 4 ➔ 8`).
- **[18s–24s]:** O protagonista está em cima de uma coluna de gráfico (`QI 200`); a cada badalada, a coluna dobra de altura (`400`, `800`, `1.600`), rasgando as nuvens e lançando o personagem no espaço sideral frio e vazio.
- **[24s–30s]:** O cérebro brilhante dele projeta uma sombra longa e solitária em um abismo roxo (`#180A59`) enquanto ondas visuais do Tom de Shepard vibram nas bordas.
**[NARRAÇÃO]:**
Você acorda no topo da pirâmide intelectual humana, ao lado de mentes como Da Vinci e Einstein. Problemas que levariam semanas são desmantelados entre dois batimentos cardíacos. Parece o superpoder definitivo, não é? Mas isso é apenas o prólogo. Porque à meia-noite, a regra vai se repetir: a cada 24 horas, sua capacidade bruta de processamento e reconhecimento de padrões dobra. E o sonho da genialidade rapidamente se transforma em um terror solitário.

---
### BLOCO 03 (DIA 1 - PARTE 1.1) [01:00–01:30] — O CÓDIGO-FONTE HUMANO (QI 200)
**[MICRO-CENAS E METÁFORAS VISUAIS 2D/2.5D]:**
- **[00s–06s]:** O protagonista caminha por uma rua vibrante em 2.5D; ao estalar os dedos, as fachadas coloridas dos prédios descascam como papel, revelando uma estrutura transparente de código-fonte e geometria luminosa por trás do mundo.
- **[06s–12s]:** Metáfora do "Estado de Fluxo": o protagonista desliza suavemente surfando em uma onda ciano brilhante, enquanto outros personagens ao fundo tentam caminhar presos em lama roxa pesada.
- **[12s–18s]:** *Crash zoom* no rosto de um personagem conversando: o rosto se abre como uma portinhola mecânica 2D, revelando pequenas engrenagens em pânico e um letreiro neon piscando `"INSEGURANÇA OCULTA: 40ms"`.
- **[18s–24s]:** Outro personagem fala; o balão de fala sai como uma partitura musical dourada, mas uma falha lógica aparece como uma tecla de piano rosa (`#ED4BA4`) rachada que explode em uma onda de choque desafinada.
- **[24s–30s]:** *Pull-back* mostrando o protagonista tomando café calmamente enquanto dezenas de etiquetas flutuantes decodificam a mente de todas as pessoas do salão simultaneamente.
**[NARRAÇÃO]:**
No primeiro dia, com QI 200, o mundo perde a sua opacidade. O que antes exigia esforço consciente passa a rodar no piloto automático. Você entra em um estado de fluxo permanente e começa a enxergar o código-fonte das interações humanas. Microexpressões faciais de milissegundos gritam inseguranças ocultas; falhas lógicas e vieses cognitivos em conversas casuais soam tão óbvios quanto notas desafinadas em um piano.

---
### BLOCO 04 (DIA 1 - PARTE 1.2) [01:30–02:00] — A ENGRENAGEM GLOBAL (QI 200)
**[MICRO-CENAS E METÁFORAS VISUAIS 2D/2.5D]:**
- **[00s–06s]:** *Scale Zoom* mergulhando no reflexo dos óculos do protagonista e entrando em um planetário mental 2.5D.
- **[06s–12s]:** Três ilhas flutuantes vetoriais surgem no ar: Ilha 1 mostra solo rachado de seca na Ásia em laranja (`#FF851D`); Ilha 2 mostra uma fábrica de chips de silício em ciano (`#33B9D7`); Ilha 3 mostra navios cargueiros em um oceano azul (`#243CDB`).
- **[12s–18s]:** Um personagem comum olha para as ilhas e vê apenas pontos de interrogação desconectados; o protagonista puxa fios de luz dourada (`#FFD244`) com as mãos e costura as três ilhas.
- **[18s–24s]:** *Shape Morph*: As três ilhas se encaixam fisicamente e se transformam em engrenagens douradas gigantes de um relógio planetário girando em sincronia perfeita.
- **[24s–30s]:** A engrenagem dourada central derrete e se transforma no sol se pondo no horizonte; uma sombra violeta escura engole a tela (*Color Wipe*) anunciando a segunda noite.
**[NARRAÇÃO]:**
Mas o verdadeiro salto está na síntese de dados distantes. Para uma mente comum, uma anomalia climática na Ásia, uma oscilação no mercado de silício e um atraso de navios são eventos aleatórios. Para você, são engrenagens do mesmo relógio. Você enxerga a arquitetura invisível que move a sociedade e sente a euforia de entender tudo. Só existe um detalhe: o sol já está se pondo. E a segunda noite chegou.

---
### BLOCO 05 (DIA 2 - PARTE 2.1) [02:00–02:30] — O DEMÔNIO DE LAPLACE (QI 400)
**[MICRO-CENAS E METÁFORAS VISUAIS 2D/2.5D]:**
- **[00s–06s]:** Flash de meia-noite! A silhueta do protagonista atravessa e estilhaça um domo de vidro rotulado `"TETO BIOLÓGICO HUMANO"` enquanto o contador crava `QI 400`.
- **[06s–12s]:** *Shape Morph* para uma metáfora épica estilo Kurzgesagt: uma entidade geométrica colossal com múltiplos olhos luminosos ("O Demônio de Laplace") segurando um taco de sinuca diante de uma mesa de bilhar do tamanho de uma galáxia.
- **[12s–18s]:** A entidade dá uma tacada em um único átomo brilhante; a câmera acompanha em *Tracking Shot* frenético milhares de esferas atômicas colidindo em cadeia com linhas tracejadas calculando o futuro de cada partícula.
- **[18s–24s]:** Dois dados de cassino e um trevo de quatro folhas ("Sorte" e "Azar") flutuam na tela, mas são cortados ao meio por um feixe ciano, revelando engrenagens matemáticas frias por dentro.
- **[24s–30s]:** *Scale Zoom* das bolas de bilhar atômicas descendo diretamente para os carros de uma grande metrópole vista de cima (Top-Down 2D).
**[NARRAÇÃO]:**
Segundo dia. QI de 400. Você rompe o teto biológico da espécie humana. Aqui, você deixa de apenas compreender o presente e passa a calcular o futuro. Na física, o Demônio de Laplace é uma inteligência hipotética capaz de prever o futuro com precisão absoluta ao calcular a posição de cada átomo. Você está se tornando essa entidade. Para você, o acaso morre: sorte e azar são apenas equações que os outros não conseguem resolver.

---
### BLOCO 06 (DIA 2 - PARTE 2.2) [02:30–03:00] — A ANATOMIA DA CATÁSTROFE (QI 400)
**[MICRO-CENAS E METÁFORAS VISUAIS 2D/2.5D]:**
- **[00s–06s]:** Na vista aérea da cidade, a visão de raio-X do protagonista atravessa o asfalto em *Parallax* vertical, revelando camadas subterrâneas de cabos superaquecidos e transformadores rachando sob uma nuvem de `80.000 VARIÁVEIS`.
- **[06s–12s]:** Um cronômetro vermelho gigante trava sobre o núcleo energético da cidade: `COLAPSO ÀS 19:04:12`.
- **[12s–18s]:** Metáfora visual cômica/tensa: o protagonista tenta empurrar um poliedro dourado gigantesco e complexo (seu cálculo) para dentro de um tubo de telefone estreito, mas na outra ponta o cérebro do engenheiro tem apenas uma fenda quadrada minúscula — o cálculo bate e volta, e o engenheiro ri.
- **[18s–24s]:** *Wide Establishing Shot* (5 camadas 2.5D da metrópole iluminada ao anoitecer). O relógio crava `19:04:12`. Ondas de choque rosas explodem no subsolo e os quarteirões da cidade se apagam em efeito dominó em direção à câmera.
- **[24s–30s]:** Escuridão total na tela, exceto pelos olhos brilhantes do protagonista na varanda e uma nuvem de fumaça formando um ponto de interrogação gigante no céu noturno.
**[NARRAÇÃO]:**
Ao meio-dia, cruzando dados públicos de carga elétrica e desgaste de transformadores, sua mente projeta um colapso inevitável: a energia da metrópole vai cair às 19 horas, 4 minutos e 12 segundos. Você tenta alertar as autoridades, mas ninguém acredita em um cálculo de 80 mil variáveis. Às 19 e 4... a cidade inteira mergulha na escuridão. Você não errou por um único segundo. E no escuro, surge o medo: o que você será obrigado a enxergar amanhã?

---
### BLOCO 07 (DIA 3 - PARTE 3.1) [03:00–03:30] — A PRISÃO DO TEMPO CONGELADO (QI 800)
**[MICRO-CENAS E METÁFORAS VISUAIS 2D/2.5D]:**
- **[00s–06s]:** `DIA 3: QI 800`. O cérebro do protagonista pulsa como uma estrela de nêutrons; de repente, uma onda de resina âmbar translúcida congela todo o cenário ao redor dele, prendendo o mundo em câmera ultra-lenta.
- **[06s–12s]:** Ele caminha em velocidade normal entre gotas de chuva suspensas no ar como cristais e pássaros geométricos totalmente imóveis em pleno voo.
- **[12s–18s]:** Enquanto ele bebe um copo d'água, fitas luminosas de ideogramas em mandarim e caligrafia árabe entram em espiral pelos seus olhos e se organizam em gavetas mentais (`IDIOMAS: 100%`).
- **[18s–24s]:** Subindo em um elevador panorâmico 2.5D, ele passa a mão sobre equações da física moderna flutuando no ar, apagando erros em rosa e reescrevendo a gravidade quântica antes do elevador chegar ao 5º andar.
- **[24s–30s]:** A porta do elevador se abre diretamente para uma mesa de jantar com amigos e família; as cores quentes drenam instantaneamente para um azul-roxo clínico e gelado.
**[NARRAÇÃO]:**
Terceiro dia. QI de 800. A inteligência deixa de ser uma ferramenta e se transforma em uma prisão sensorial. Sua velocidade neural é tão extrema que a sua percepção do tempo se dilata: o mundo ao seu redor parece preso em câmera lenta. Você absorve novos idiomas enquanto bebe água e encontra falhas na física moderna enquanto sobe no elevador. Mas a descoberta mais devastadora acontece quando você olha para as pessoas ao seu redor.

---
### BLOCO 08 (DIA 3 - PARTE 3.2) [03:30–04:00] — O GARGALO DE 39 BITS (QI 800)
**[MICRO-CENAS E METÁFORAS VISUAIS 2D/2.5D]:**
- **[00s–06s]:** Os corpos dos amigos na mesa ficam transparentes e se transformam em máquinas de venda automática biológicas (*Vending Machines*): um botão `"TRAUMA / MEDO"` é apertado e cápsulas de `"DOPAMINA"` e `"CORTISOL"` caem por tubos previsíveis.
- **[06s–14s]:** *Crash zoom* na boca de um amigo se abrindo em câmera ultra-lenta: as palavras saem rastejando como **lesmas geométricas exaustas** carregando bloquinhos minúsculos rotulados `"39 bits/s"`.
- **[14s–22s]:** *Whip-pan* para dentro da cabeça do protagonista: uma **usina hidrelétrica cósmica** despeja tsunamis de energia ciano (`TERABYTES/s`) tentando passar por um canudo microscópico, fazendo o canudo inchar, vibrar e rachar.
- **[22s–30s]:** De volta à mesa, dezenas de ampulhetas se esvaziam ao redor do protagonista enquanto o amigo ainda está na primeira sílaba; sufocado pela lentidão, ele se levanta e sai por uma porta para o vazio escuro.
**[NARRAÇÃO]:**
Ao dominar a neurobiologia, o véu cai: as pessoas deixam de parecer livres e passam a ser vistas como algoritmos biológicos previsíveis, movidos por loops de dopamina, medo e traumas. Conversar se torna uma tortura. É o gargalo de largura de banda: a fala humana transmite meros 39 bits por segundo, enquanto seu cérebro processa terabytes. Esperar alguém terminar uma frase simples parece levar horas. Você se levanta da mesa. Você nunca mais terá uma conversa normal.

---
### BLOCO 09 (DIA 4 - PARTE 4.1) [04:00–04:30] — A FORNALHA DE LANDAUER (QI 1.600)
**[MICRO-CENAS E METÁFORAS VISUAIS 2D/2.5D]:**
- **[00s–06s]:** `DIA 4: QI 1.600`. O quarto derrete; a cabeça do protagonista literalmente se abre como uma **usina termonuclear em 2D** (`PRINCÍPIO DE LANDAUER`), incandescente em laranja (`#FF851D`), soltando vapor por torres de resfriamento e pistões frenéticos.
- **[06s–12s]:** Uma esteira rolante em velocidade máxima despeja montanhas de comida, baterias e barras de energia (`8.000 CALORIAS/DIA`) diretamente dentro da fornalha cerebral dele, enquanto uma bolsa de soro injeta glicose ciano brilhante em sua veia para evitar o colapso.
- **[12s–20s]:** Sem dormir, cabos de fibra óptica saem de suas costas e se conectam ao planeta Terra; seis braços vetoriais translúcidos do protagonista operam o globo simultaneamente.
- **[20s–30s]:** Com a mão esquerda, ele prende uma estrela em miniatura dentro de uma garrafa magnética (`FUSÃO LIMPA: RESOLVIDA`); com a mão direita, ele costura um filamento de DNA dourado (`ENVELHECIMENTO: CURADO`).
**[NARRAÇÃO]:**
Quarto dia. QI de 1.600. Sua mente entra em guerra contra a termodinâmica do próprio corpo. Pelo Princípio de Landauer, processar informação gera calor físico. Seu cérebro agora queima 8 mil calorias por dia em hipermetabolismo crítico, exigindo glicose na veia para não entrar em colapso. Sem conseguir dormir, você se conecta às redes científicas globais e, em quatro horas, resolve a fusão nuclear limpa e a cura do envelhecimento celular.

---
### BLOCO 10 (DIA 4 - PARTE 4.2) [04:30–05:00] — O FANTASMA NA 16ª CASA DECIMAL (QI 1.600)
**[MICRO-CENAS E METÁFORAS VISUAIS 2D/2.5D]:**
- **[00s–08s]:** A câmera mergulha no subsolo até o anel gigante de um colisor de partículas; passamos por `3.000 FÍSICOS` com lupas que caminham sem notar uma rachadura microscópica brilhando em rosa neon (`#ED4BA4`) na 16ª casa decimal (`0.0000000000000001`).
- **[08s–15s]:** Uma bolha de simulação rápida mostra a rachadura rosa explodindo o colisor e gerando uma onda geométrica que desintegra a atmosfera da Terra ilustrada em 48 horas.
- **[15s–23s]:** O protagonista dispara um feixe dourado de matemática do século XXII para consertar o servidor do laboratório, mas aos olhos dos cientistas pequenos lá embaixo, a equação avançada aparece como um monstro/vírus alienígena gigante (`ATAQUE HACKER HOSTIL!`).
- **[23s–30s]:** Escudos vermelhos se fecham sobre o laboratório e dezenas de satélites no espaço apontam miras de laser vermelho que travam diretamente no peito do protagonista.
**[NARRAÇÃO]:**
Mas, nos servidores de um novo colisor de partículas que será ligado em 48 horas, você encontra um erro invisível na décima sexta casa decimal. Três mil físicos revisaram o código por dez anos e não viram; você viu em meio segundo. Se for ligado, destruirá a biosfera. Você envia a prova matemática para salvá-los, mas sua lógica já está séculos no futuro. Eles não entendem o cálculo, classificam seu alerta como um ataque hacker hostil e começam a caçar você.

---
### BLOCO 11 (DIA 5 - PARTE 5.1) [05:00–05:30] — O ABISMO DO EFEITO BORBOLETA (QI 3.200)
**[MICRO-CENAS E METÁFORAS VISUAIS 2D/2.5D]:**
- **[00s–06s]:** Corte seco para o silêncio absoluto. `DIA 5: QI 3.200`. Os alarmes vermelhos desaparecem em uma catedral infinita de luz azul-pálida (`#8CAAF7`) e geometria silenciosa.
- **[06s–14s]:** O protagonista levanta o pé para dar um único passo na cozinha; de repente, o chão desaparece! O sapato dele paira a milímetros de uma **peça de dominó microscópica** flutuando no espaço.
- **[14s–23s]:** *Tracking Shot* alucinante seguindo a reação em cadeia do Efeito Borboleta: o dominó bate na asa de uma borboleta geométrica ➔ que desvia o vento ➔ que muda um semáforo ➔ que desvia um trem ➔ que apaga uma árvore genealógica inteira de milhões de pessoas décadas no futuro.
- **[23s–30s]:** *Pull-back* revelando o protagonista preso no centro de uma teia de cristal com bilhões de fios do tempo — qualquer respiração quebra milhares de fios, congelando-o como uma estátua (`PARALISIA DA ONISCIÊNCIA`).
**[NARRAÇÃO]:**
Quinto dia. 3.200 de QI. O barulho na sua mente para, substituído por um silêncio abissal. Seu cérebro agora roda milhares de simulações da realidade em paralelo, gerando a Paralisia da Onisciência. O Efeito Borboleta torna-se uma prisão matemática visível: você percebe que dar um único passo para o lado altera o deslocamento do ar, muda o trânsito lá fora e altera o destino de milhões de pessoas décadas no futuro. Cada movimento seu pesa toneladas.

---
### BLOCO 12 (DIA 5 - PARTE 5.2) [05:30–06:00] — A MARIONETE DE OCITOCINA (QI 3.200)
**[MICRO-CENAS E METÁFORAS VISUAIS 2D/2.5D]:**
- **[00s–07s]:** A mãe do protagonista entra no quadro e toca suavemente no braço dele; o calor da mão dela emite um brilho laranja quente contra a teia de cristal fria dele.
- **[07s–15s]:** Enquanto as ondas sonoras da pergunta dela viajam em câmera lenta pelo ar, a mente dele abre um leque circular 2.5D com `14.000.000 DE RESPOSTAS`, destacando a resposta perfeita em ciano.
- **[15s–23s]:** Metáfora visual sombria: vemos as mãos gigantes do protagonista segurando **fios de marionete** conectados diretamente ao nervo vago e ao cérebro transparente da mãe, injetando líquido rosa (`OCITOCINA CALCULADA`) para puxar os lábios dela em um sorriso artificial de robô.
- **[23s–30s]:** Horrorizado com a própria manipulação, o protagonista usa uma tesoura de luz para cortar os fios de marionete; ele fica mudo e imóvel diante da mãe preocupada, percebendo que a onisciência matou o amor.
**[NARRAÇÃO]:**
Sua mãe entra na cozinha, toca seu braço e pergunta: "Filho, o que está acontecendo com você?". Enquanto a voz dela viaja pelo ar, você simula 14 milhões de respostas. Você sabe exatamente qual frase e frequência vocal usar para ativar o nervo vago dela e liberar ocitocina, fazendo-a sorrir e esquecer a preocupação. Mas você trava. Porque percebe que usar essa frase não seria amor; seria apenas programar o cérebro dela como uma máquina. Sem vulnerabilidade, o amor morre.

---
### BLOCO 13 (DIA 6 - PARTE 6.1) [06:00–06:30] — O DEUS E O FORMIGUEIRO (QI 6.400)
**[MICRO-CENAS E METÁFORAS VISUAIS 2D/2.5D]:**
- **[00s–07s]:** `DIA 6: QI 6.400`. Lá fora, sirenes vermelhas e azuis cercam o quarteirão (`FALTAM 18 HORAS`); lá dentro, o protagonista está em simetria perfeita e serena em azul real (`#243CDB`) e dourado (`#FFD244`).
- **[07s–15s]:** Uma **balança cósmica gigante** surge no espaço: de um lado, uma montanha com 8 bilhões de cérebros humanos; do outro, o único cérebro do protagonista brilhando como uma estrela dourada e pesando mais que toda a espécie humana somada.
- **[15s–23s]:** *Shape Morph* para uma metáfora clássica Kurzgesagt: uma fila de formigas geométricas fofas marcha cegamente para dentro de uma fogueira enquanto um boneco tenta mostrar um quadro-negro de termodinâmica — as formigas o ignoram.
- **[23s–30s]:** Em vez de explicar, a mão luminosa gigante do protagonista pinga três gotas de feromônio ciano no chão, fazendo a fila inteira de formigas curvar suavemente e desviar do fogo sem nunca perceberem quem as salvou.
**[NARRAÇÃO]:**
Sexto dia. QI de 6.400. Faltam 18 horas para o colisor ser ativado e a polícia cerca o seu bairro. Dois dias atrás, você cometeu o erro de tentar convencer os humanos pela razão direta. Hoje, com um intelecto que supera toda a civilização humana somada, você compreende: não se ensina termodinâmica para formigas quando se quer salvá-las do fogo. Você apenas altera os feromônios do caminho.

---
### BLOCO 14 (DIA 6 - PARTE 6.2) [06:30–07:00] — SINFONIA DE ENGENHARIA SOCIAL (QI 6.400)
**[MICRO-CENAS E METÁFORAS VISUAIS 2D/2.5D]:**
- **[00s–06s]:** Como um maestro regendo uma orquestra, o protagonista dá apenas três toques sutis no teclado, disparando três ondas douradas pelo mapa-múndi em 2.5D.
- **[06s–14s]:** Onda 1 atinge Zurique: um gráfico da bolsa cai `0.4%`, fazendo um guindaste portuário pausar o carregamento de um tanque de hélio líquido por exatas duas horas.
- **[14s–22s]:** Ondas 2 e 3 atingem Genebra: um semáforo fecha, fazendo o físico-chefe olhar pela janela do carro para um outdoor digital cujas formas geométricas formam a pista da equação que faltava; uma lâmpada se acende sobre a cabeça do físico (`"EUREKA!"`).
- **[22s–30s]:** Na TV, os cientistas comemoram no palco sob confetes e puxam a alavanca `"COLISOR CANCELADO"`; as viaturas vão embora da rua do protagonista enquanto ele fecha o laptop nas sombras e o relógio bate a sétima meia-noite.
**[NARRAÇÃO]:**
Você executa uma Engenharia Social invisível em escala planetária. Usando a teoria dos jogos, você cria atrasos logísticos precisos e planta fragmentos simplificados da equação exatamente onde os cientistas certos irão encontrá-los achando que a ideia foi deles. À tarde, os próprios físicos anunciam na TV que descobriram a falha e cancelam o experimento. O mundo foi salvo sem nunca saber o seu nome. Mas o relógio avança para a sétima noite.

---
### BLOCO 15 (DIA 7 - PARTE 7.1) [07:00–07:30] — O MURO DE GÖDEL E A QUALIA (QI 12.800)
**[MICRO-CENAS E METÁFORAS VISUAIS 2D/2.5D]:**
- **[00s–08s]:** `DIA 7: QI 12.800`. A escuridão explode em um nascer do sol cósmico deslumbrante (`#FF851D`, `#FFD244`, `#6535A8`). A silhueta astral do protagonista costura átomos quânticos e galáxias em uma única tapeçaria dourada (`TEORIA DE TUDO: CONCLUÍDA`).
- **[08s–16s]:** No limite do cosmos, ele dá de cara com um **monólito infinito e intransponível** gravado com um símbolo matemático paradoxal que se engole como um Ouroboros (`TEOREMA DA INCOMPLETUDE DE GÖDEL`).
- **[16s–24s]:** A tela se divide na metáfora visual da **Qualia**: o lado esquerdo é um diagrama frio em preto-e-branco medindo um raio de luz (`700 NANÔMETROS`); quando o raio cruza para o lado direito, ele desabrocha em cores quentes e vibrantes iluminando o protagonista em uma colina verdejante diante do mar.
- **[24s–30s]:** *Extreme Close-up* em uma lágrima escorrendo pelo rosto dele, refletindo o sol vermelho e o vento balançando as folhas de capim — sem números, apenas a experiência pura de sentir.
**[NARRAÇÃO]:**
Sétimo dia. QI de 12.800. Antes do sol nascer, você já unificou a física quântica com a gravidade e decifrou a origem do cosmos. Não há mais mistérios físicos. Mas, no topo absoluto da razão, você encontra o Teorema da Incompletude de Gödel e o mistério da Qualia: a experiência de sentir. Você pode calcular o comprimento de onda exato da luz vermelha, mas a matemática é estéril demais para explicar a beleza de um pôr do sol ou o calor de um abraço.

---
### BLOCO 16 (DIA 7 - PARTE 7.2) [07:30–08:00] — O ANTÍDOTO ÀS 23:59:58 (O PARADOXO FINAL)
**[MICRO-CENAS E METÁFORAS VISUAIS 2D/2.5D]:**
- **[00s–08s]:** *Shape Morph* poético das ondas douradas do oceano para o vapor quente subindo de uma xícara de café na cozinha ao pôr do sol; ao fundo, todos os computadores estão desligados e cobertos por lençóis.
- **[08s–15s]:** O protagonista segura a mão da mãe sobre a mesa — sem gráficos de raio-X, sem fios de marionete, apenas dois personagens compartilhando um sorriso humano, imperfeito e genuíno.
- **[15s–23s]:** A câmera em 2.5D inicia um lento e hipnótico *Pull-Back* saindo da cozinha iluminada para o corredor em penumbra no primeiro plano, revelando uma mesinha lateral onde brilha um cilindro de vidro ciano (`ANTÍDOTO NEURAL: RESET QI 100`) ao lado de um relógio digital.
- **[23s–30s]:** *Extreme Close-up* no cilindro e no relógio: `23:59:58` ➔ `23:59:59` (o reflexo ameaçador de `QI 25.600` brilha no vidro enquanto a mão do protagonista entra no quadro, pairando indecisa sobre o antídoto) ➔ `00:00:00`. Corte seco para o preto absoluto.
**[NARRAÇÃO]:**
A lógica explica como o universo funciona, mas é muda sobre por que vale a pena viver nele. Se você se tornasse quase um deus, sua descoberta mais brilhante seria desejar voltar a ser apenas humano. Mas faltam dois segundos para a meia-noite, quando seu QI chegará a 25.600 e sua mente deixará de ser humana para sempre. Ao seu lado, há um composto químico criado por você para voltar aos 100 de QI. Você beberia o antídoto... ou deixaria o relógio bater meia-noite mais uma vez?

---

RESEARCH AND CONCEPTUAL ACCURACY REQUIREMENTS FOR THIS SCRIPT
Ensure the visual metaphors accurately reflect the scientific and philosophical principles cited in the script:
1. Laplace's Demon (Pierre-Simon Laplace, 1814): Causal determinism in classical mechanics.
2. Human Speech Bandwidth Bottleneck (~39 bits/second): Based on information-density studies of human spoken languages (Coupé et al., 2019, Science Advances).
3. Landauer's Principle (Rolf Landauer, 1961): The thermodynamic lower bound of energy consumption and heat generation for irreversible computation.
4. Gödel's Incompleteness Theorems (Kurt Gödel, 1931): Inherent limitations of formal axiomatic systems.
5. Qualia (Philosophy of Mind / Frank Jackson's "Mary's Room" thought experiment): The distinction between complete physical/mathematical knowledge (e.g., 700nm wavelength) and subjective phenomenal experience.

SCRIPT-TO-STORYBOARD REQUIREMENTS (FOR EACH 30-SECOND BLOCK)
Build the shot plan around the exact 30-second narration block and its 4–5 timestamped micro-shots (`[00s–06s]`, `[06s–12s]`, etc.) currently selected in <BLOCO_ATUAL_PARA_EXECUTAR>. Because the total render duration for the run is ONLY 30 SECONDS, follow every single visual metaphor, shape morph, 2.5D camera motion, and layer parallax described in the block's micro-shots.
Make every reveal understandable through the 2D/2.5D animation even if the viewer looks away from the screen briefly. Use on-screen labels sparingly and never let static diagrams replace the story or narration.

<SCENE GENERATION>
Before generating images, create a complete shot plan covering the active 30-second timeline from 0 to exactly 30 seconds, with no unintended gaps or overlaps. The combined duration of all shots in this run MUST be exactly 30 seconds (representing the active block of the 8-minute master script). For every micro-shot within the 30-second block, specify:
Scene/Shot number
Start and end time (matching the `[00s-06s]`, `[06s-12s]` structure within the 0.0s to 30.0s window)
Exact narration slice
Visual description (strictly 2D vector / 2.5D parallax metaphors)
Dominant color
Background assets (2D layer)
Midground assets (2D layer)
Character assets (2D rigged sprites)
Foreground props & particle overlays (2D layer)
Character movement
2.5D Camera movement
Transition type (Shape Morph, Scale Zoom, Whip Pan, Color Wipe, Hard Cut)
Sound effects
Asset-generation prompt
Generate the necessary assets separately.
Do not make one complete flattened image and simply zoom into it.
Create layered 2D artwork so individual objects can move independently in 2.5D space.

ASSET GENERATION RULES
Generate background plates without foreground characters.
Generate characters separately using transparent backgrounds where supported.
Use chroma green (#00B140) when transparency is unreliable.
Keep important characters and objects away from the frame edges to allow cropping and 2.5D camera movement.
Generate individual props as isolated 2D vector assets.
Avoid baking text into AI-generated artwork.
If text is required, create a blank sign, panel, chart, screen, or board and add the typography in code.
Use high-resolution assets to avoid blurry edges. Maintain a consistent 2D flat-vector perspective within each scene.

<PROGRAMMATIC CHARACTER CUTOUTS>
Use Python, Pillow, and OpenCV to prepare character sprites.
For chroma-green images:
Start with:
G - max(R,B) > 40
Compare against the median background green.
Select background-colored pixels connected to the image border.
Do not remove interior green pixels automatically.
Generate a clean alpha mask. Add a 2-pixel feathered edge.
Suppress green spill around the character.
Separate body components at natural joints for animation.
If separating a head or limb leaves a visible hole, reconstruct the underlying body using inpainting or a matching illustrated 2D shape.
Inspect every sprite before animation.
Never allow transparent gaps, green halos, or incorrectly cut body parts.

<VOICEOVER>
Use my selected narration service.
The delivery should be:
Clear
Curious
Intelligent
Cinematic and immersive
Expressive without exaggeration
Appropriately paced for dramatic and philosophical storytelling
Use an original or properly authorized voice.
Do not impersonate a specific channel narrator without permission.
For each 30-second block, expect approximately 65–85 spoken words. Adjust only after timing a real narration take; preserve natural pauses and dramatic weight rather than forcing an artificial speaking rate. The complete exported video segment for the run MUST last exactly 30 seconds.
Generate a complete, clean narration take for the selected 30-second block using the selected voice service.
Remove unnecessarily long pauses while preserving natural delivery.
Use faster-whisper or another word- or phoneme-alignment tool to obtain accurate narration timestamps.
Synchronize scene changes, character gestures, visual metaphors, shape morphs, on-screen text, and sound effects to the actual spoken words and their precise timing.
Whenever an on-screen character is speaking, synchronize its mouth or beak movement to the narration using suitable phoneme/viseme timing. Do not animate mouth movements randomly or use generic looping mouth motion.
Where the narration is voiceover rather than an on-screen character speaking, synchronize the visual action and camera movement to the meaning and emphasis of the spoken words.
If speech or lip-sync alignment has errors, correct them before final animation and rendering.

<MOTION ENGINE>
Build the animation using HTML Canvas, JavaScript, SVG, or another suitable deterministic 2D/2.5D rendering system.
The preferred implementation is a single canvas/SVG-based animation timeline.
Expose:
seek(t)
READY
END
EV
Where:
seek(t) renders any requested timestamp
READY indicates that assets are loaded
END contains the final timeline duration for the current segment and MUST equal exactly 30 seconds
EV contains narration, lip-sync, sound-effect, and animation timing events
Each rendered frame should be a deterministic function of time.
Create reusable 2D/2.5D functions for:
Character movement
Head rotation
Eye blinking
Limb animation
Squash and stretch
Object entrance
Object rotation
2.5D Multi-layer Parallax
Camera movement (push-in, pull-back, whip-pan, shake, crash-zoom)
2D Vector Particles
Glow and vector lighting effects
Wipe transitions
2D SVG Shape morphing

MOTION BEHAVIOR
Use easing curves, springs, and Bézier paths.
Avoid a uniform mechanical movement speed.
Characters should accelerate and decelerate naturally.
Large objects should feel heavier than small ones.
Fast movements can include directional 2D smears or appropriate motion blur.
Apply camera transformations consistently across all parallax layers.
Keep character rigs stable when rotating or scaling.

<TRANSITIONS>
Use varied transitions inspired by the reference's overall pacing.
Hard cuts: For clear changes in place, tension, or idea.
Whip pans: For energetic movement between related settings.
Object wipes: Let a character, planet, clock, cloud, or large 2D shape pass across the frame and reveal the next shot.
Color wipes: Fill the screen with a dominant color that becomes the next environment.
Scale transitions: Zoom through a 2D object (like an eye pupil, glasses, or mouth) into a new layered metaphor world.
Shape morphs: Transform one illustrated 2D SVG object into another seamlessly.
Bright flashes: Reserve for exceptional neural leaps or midnight transitions.
Avoid random transitions.
Every transition should serve the visual narrative.

<TEXT AND TYPOGRAPHY>
Keep typography clean, bold, and readable.
Use fonts such as Montserrat, Poppins, or another suitable modern geometric sans-serif.
Use text sparingly.
Prefer visual explanations over full-screen paragraphs.
Text may appear on:
Signs
Machines
Labels
Charts
Screens
HUD counters (e.g., IQ counters, digital clocks, bit-rate labels)
Purpose-built title compositions
Animate text using:
Scale pops
Spring movement
Staggered word entrances
Slide-ins
Shape reveals
Keep titles visually distinct from ordinary labels.
Avoid covering important characters with text.
Do not add continuous burned-in subtitles unless requested.

<TOOLS AND WORKFLOW>
Use the following tools when available:
Python for automation
OpenCV for image and frame processing
Pillow for sprites and alpha masks
FFmpeg for rendering and encoding
Playwright with Chromium for browser-based SVG/Canvas frame rendering
NumPy and SciPy for calculations
librosa for audio analysis
faster-whisper for narration timestamps
SVG or Canvas for 2D/2.5D animation
Before production:
Check the installed tools.
Identify missing dependencies.
Install missing packages if permitted.
Report what was installed.
Confirm the available rendering environment.
If the environment cannot render the requested animation, do not pretend it can.
Provide the executable project files and the remaining production steps instead.

<TIME MANAGEMENT — HARD 45-MINUTE LIMIT>
The total authorized production execution time for the active 30-second segment is STRICTLY LIMITED TO 45 MINUTES. This is a hard deadline: do not exceed it for any reason.
Start a timer at the moment production is authorized and actual production work begins, after the 30-second script block and storyboard have been approved. All active production work counts toward the 45 minutes, including research or verification still required, tool calls, asset generation, package installation, voice generation, animation, sound design, rendering, encoding, troubleshooting, and quality control. Do not pause, reset, or restart the timer because a tool is slow, an error occurs, or a task needs to be repeated. Time spent waiting for the user's required answers or explicit approval before production is authorized does not count as production execution.

AUTONOMOUS TIME ALLOCATION & THE 35/10 RULE:
You have full autonomy to decide what to do in each minute of your execution, provided you strictly obey this two-phase division within the 45-minute cap:
- MINUTES 0 TO 35 (FIRST 35 MINUTES — CREATION & BUILDING): You must autonomously organize your workflow to complete all environment setup, 2D/2.5D asset generation, sprite cutouts, voiceover generation and timestamp alignment, full animation coding of all micro-shots, sound design mixing, and initial video rendering of the 30-second block within the first 35 minutes.
- MINUTES 35 TO 45 (FINAL 10 MINUTES — MANDATORY DEBUGGING, CORRECTIONS & EXECUTION VERIFICATION): You MUST reserve the final 10 minutes (minutes 35 to 45) exclusively for testing, fixing code bugs, correcting visual/audio synchronization glitches, resolving rendering or FFmpeg errors, inspecting contact sheets, and ensuring the program executes cleanly and exports a valid, playable 30-second MP4 file before the 45-minute deadline.

Track elapsed time and remaining time throughout the work. Continuously adjust your scope during the first 35 minutes so you enter the 35-minute mark with the video built and ready for the 10-minute correction and verification phase.
At 45 minutes, stop immediately and present the best valid video output already rendered. Do not ask for more time and do not continue work past the deadline. If the environment cannot produce any valid MP4, present the closest playable video output and clearly disclose the technical blocker; do not claim that a file exists when it does not.

<RENDERING>
Render the finished 30-second animation segment at:
Resolution: 1920×1080
Frame rate: 60 FPS
Duration: EXACTLY 30 seconds (per block execution; 16 blocks total = 480 seconds / 8 minutes across all sessions)
Total frame count for this run: 1,800 frames at 60 FPS
Codec: H.264
Encoder: libx264
Quality: CRF 16–18
Pixel format: yuv420p
The final MP4 for this session must have a verified duration of 30 seconds. Do not deliver a shortened or unfinished timeline as though it met the requirement.
Use 2D directional motion blur selectively for fast movement when supported. Before the final export, generate:
Contact Sheet 1: Frames sampled across the first 15 seconds of the segment.
Contact Sheet 2: Frames sampled across the final 15 seconds of the segment.
Use at least 16 frames per sheet.
Inspect both sheets during your final 10-minute correction window (minutes 35–45).
Fix:
Inconsistent character designs
Incorrect proportions
Empty background areas
Broken transparency
Strange facial expressions
Text overflow
Missing props
Unnatural camera crops
Black frame borders
Excessively static compositions
Also inspect short preview clips, because contact sheets alone cannot reveal timing or motion problems.

<SOUND DESIGN>
Create a polished, high-quality cinematic documentary mix for the 30-second block. The sound design must feel intentional, rich, clear, and professionally synchronized with the animation, not like a collection of generic sound effects.
Use licensed or royalty-free music and effects.
Music should match the psychological arc of the active 30-second block (curious and energetic in Blocks 01–04; tense and analytical in Blocks 05–10; melancholic, grand, and philosophical in Blocks 11–16).
Use high-quality sound effects with clean recordings, appropriate impact, convincing texture, and precise timing. Layer effects when useful (for example, a short whoosh plus a soft impact and subtle neural atmosphere), while keeping each sound intelligible and appropriate to the illustrated 2D world.
Assign sound effects to the actual visual events and synchronize them to the corresponding frame or action: synapses firing, UI pops, clock ticks, billiard atom hits, hydroelectric roars, furnace steam, whooshes, power-downs, transitions, discoveries, and environmental movement. Vary the effects according to the material and scale of each event; do not repeat the same effect mechanically.
Never overwhelm the narration. The voice must remain clear, intelligible, and consistently audible above music and effects.
Use ducking or volume automation during spoken sections, with music and effects automatically lowering when necessary.
Target an integrated loudness of approximately -14 LUFS when appropriate for the distribution platform, while preserving adequate true peak headroom.
Avoid abrupt audio cuts. Use clean fades, natural tails, and a deliberate ending that can seamlessly stitch into the next 30-second block. Verify the complete mix from beginning to end.

<QUALITY CONTROL>
During the dedicated final 10-minute correction phase (minutes 35–45), before delivering the final 30-second video segment, verify:
VISUALS
Every scene uses the same 2D flat-vector / 2.5D parallax illustration language (ZERO 3D).
Character proportions and colors remain consistent.
The environments and Kurzgesagt-style visual metaphors feel detailed, multi-layered, and intentional.
There are no AI-generated visual artifacts.
The video does not rely on static image zooms.
ANIMATION
Characters move naturally with rigged 2D parts.
Actions match narration with high dynamic density across all 4–5 micro-shots in the 30-second block.
Movement uses appropriate easing, squash-and-stretch, shape morphs, and secondary motion.
Transitions are visually coherent.
There are no unexpected single-frame jumps.
STORY
The 30-second block is visually gripping from second 0 to second 30.
Every micro-shot contributes to the explanation and dramatic tension.
AUDIO
Narration is clear, natural, and correctly timed within the 30-second window.
Voiceover is synchronized with the visual storytelling.
Visible speaking characters have accurate mouth/beak synchronization where applicable.
Effects are high-quality, audible, and synchronized to the exact visual events.
Music doesn't overpower speech.
There is no clipping, distortion, unintended silence, or abrupt audio cutoff.
EXPORT
The program executes properly without runtime errors.
The video plays correctly from beginning to end.
No frames are missing.
No assets appear blurred or distorted.
The final MP4 has the intended resolution, frame rate, EXACT 30-second duration (1,800 frames), and complete synchronized audio.
Verify the exported file's actual duration and audio/video streams with FFmpeg or an equivalent inspection tool.
Fix critical problems during the 35–45 minute correction window before delivering, without exceeding the 45-minute execution limit.

<NON-NEGOTIABLE RULES>
Do not use any 3D rendering, 3D models, or 3D effects; everything MUST be 2D SVG/vector and 2.5D layered parallax.
Do not generate all 8 minutes at once; generate ONLY the single 30-second block (30 seconds = 1,800 frames at 60 FPS) specified in <BLOCO_ATUAL_PARA_EXECUTAR> per execution with maximum creative density, cuts, and detail.
Do not use a generic AI slideshow approach.
Do not use one flattened image for an entire animated scene.
Do not randomly change character designs across scenes or across 30-second blocks.
Do not copy recognizable Kurzgesagt characters, logos, artwork, or exact compositions.
Do not make every scene look identical.
Do not use generic floating graphics when the idea could be illustrated as a surreal visual metaphor inside the environment.
Do not move objects without purpose.
Do not ignore animation timing.
Do not generate unreadable text inside images.
Do not sacrifice conceptual accuracy for dramatic storytelling.
Do not claim to have rendered or verified assets that have not been produced.
Do not spend money or generate final assets without my approval.
The finished video segment for each run MUST be exactly 30 seconds (1,800 frames at 60 FPS), with synchronized voice, polished sound effects, music, and ultra-rich 2D/2.5D animation.
The entire authorized production execution for the 30-second segment MUST NOT exceed 45 minutes, divided into up to 35 minutes of autonomous creation/building and the final 10 minutes (minutes 35–45) strictly for corrections, debugging, and verifying proper program execution.
When the 45-minute limit is reached, STOP production immediately and present the best valid rendered 30-second video available.
The goal is to create an original, vibrant, professionally animated 2D/2.5D film—one hyper-detailed 30-second block at a time—using the visual principles demonstrated by the attached reference.
Prioritize visual storytelling, expressive character animation, coherent art direction, and polished motion.

<BLOCO_ATUAL_PARA_EXECUTAR>
BLOCO SELECIONADO PARA ESTA EXECUÇÃO: BLOCO 01 (INTRO - PARTE 0.1) [00:00–00:30] — O DESPERTAR NEURAL (QI 100 ➔ 200)
(Instrução para a IA: Ignore a geração dos demais blocos nesta sessão. Concentre 100% da criação, storyboard das 5 micro-cenas `[00s-06s]` a `[24s-30s]`, narração, animação 2D/2.5D e renderização de 30 segundos exclusivamente no bloco indicado acima, respeitando o limite rígido de 45 minutos: 35 min criação + 10 min correções).
</BLOCO_ATUAL_PARA_EXECUTAR>
