- 👋 Hi, I’m @maxumss
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
maxumss/maxumss is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your Example file showing a circle moving on screenwa
import pygame import random
# pygame setup
pygame. init()
screen = pygame.display.set_mode((1280, 720))
cLock = pygame. time.Clock()
running = True
dt = 0
fst_pos = pygame.Vector2(screen.get width() / 2, screen.get_height) / 2)
Fst_pos = pygame. Vector2(screen.get width() / 2, screen.get_height() / 2)
sec_pos - pygame. Vector2(screen.get_width() / 2, screen.get_height) / 2)
trd_pos = pygame. Vector2(screen.get_width() / 2, screen.get_height() / 2)
while running:
# poll for events
# pygame.QuIT event
means the user clicked X to close your window
for event in pygame.event.get(: if event.type == pygame. QUIT:
running = False
# fill the screen with a color to wipe away anything from last frame-
screen.fill("dark blue")
square = pygame. Surface ((40, 40))
square,fill"green")
pygame. rect. Rect (10,10 ,10 ,10)
rect = square.get_rect (center • (1280//2 , 720//2)) pygame. draw. rect (screen, colors
"green" , rect )
keys = pygame.key get_pressed()
pos = pygame.mouse.get_pos()
