ESSAzLife DaisyBelle — rebuild
================================
Open index.html in a browser, or use VS Code Live Server for best results. The game fills the browser viewport; install as a PWA for an app-like experience.

IMPORTANT: The original room, outfit, food, drink, game and bath artwork shown in your screenshots is NOT present as image files in this ZIP. Copy your own original .png files into the matching folders, using the filenames shown below. The fridge.png included here is the refrigerator image supplied earlier. The seven previously available voice recordings are included; newly recorded voices need to be copied into Voice/ yourself.

ROOMS:
Rooms/living room/living-grey.png (and living-beach, living-colors, living-cow, living-daisy, living-green, living-halloween, living-pink, living-thanksgiving, living-xmas, living-yellow)
Rooms/kitchen/white.png (also beach, christmas, grey, halloween, plaid, sky, thanksgiving)
Rooms/bathroom/white.png (same wallpaper names as kitchen)
Rooms/bedroom/pink-bed-day.png and pink-bed-night.png (also grey-bed, nascar-bed, winter-bed day/night pairs)
Rooms/backyard/warmbackyard.png (also autumnbackyard, winterbackyard)

OUTFITS: Outfits/blue-outfit.png, brown-outfit.png, green-outfit.png, orange-outfit.png, pajama-outfit.png, princess-outfit.png, red-outfit.png, yellow-outfit.png
BATH: bath/shower-head.png, bath/pink-soap.png, bath/fur-dryer.png
FRISBEE: Games/frisbee.png
COIN: coin/gold-moocow-coin.png
FOOD & DRINKS: See script.js foods/drinks arrays for filenames.

VOICE FILES (Voice/):
Previously available: bedroom.m4a, dressed-up.m4a, feed-me.m4a, princess-dress-react.m4a, return.m4a, snoring.m4a, stinky.m4a.
New: burp.m4a, om-nom-nom.m4a, thats-enough-slices.m4a, wasnt-even-sleeping.m4a, awe-shucks.m4a, i-have-a-lawyer.m4a, stop-poking-me.m4a, good-for-you.m4a, woo-hoo.m4a, christmas-money.m4a, bathroom.m4a, school-bad-day.m4a, school-good-day.m4a, frisbee-third-throw.m4a, frisbee-fourth-throw.m4a, frisbee-fifth-throw.m4a, its-you.m4a, frisbee-miss.m4a. Files absent will simply fail silently. 'catch-these-hooves' is NOT used.

TEST CHRISTMAS: Open developer console and run:
DaisyBelleDebug.setDate('2026-12-10T16:00:00')
To reset: DaisyBelleDebug.resetDate()
TEST SCHOOL: DaisyBelleDebug.setDate('2026-11-10T10:00:00')

School normal mode uses 9:00 AM–3:00 PM. Stay Home All Day is in Settings. School reports use weekly grades and a 500-coin reward after 3 Great Days. Wallpapers cost 100 coins each, except currently selected ones.

NOTE: User artwork needs copying into the folders before this game will visually match your screenshots. The school sign and Christmas tree are CSS/emoji approximations, not exact copies of the user-supplied reference art. The frisbee and mini-games are functional JavaScript implementations but need device testing.

TARGETED FIXES (2026-11-10)
- School at 9 AM to 3 PM, slide left with Voice/see-ya.m4a; school sign follows.
- School report shows 'Send DaisyBelle Back to School' if she was brought home early during school hours; day becomes Okay ('meh').
- Early pickup and regular dismissal restore all five care needs to 50%.
- Wallpapers now show price and confirmation before deducting MooCow Coins.
- Pop-on-tap sound for mini-game selections; objective-met for matching groups/pairs.
- ESSA Tiles tray-full loss plays woo-hoo.
- Level-up plays level-up and awards 600 MooCow Coins with popup.
- Swipe petting uses Voice/awe-shucks.m4a (already hooked up).
- Console commands: DaisyBelleDebug.school(), DaisyBelleDebug.christmas(), DaisyBelleDebug.resetDate(), DaisyBelleDebug.resetSchoolToday().
IMPORTANT: New recordings from your PC are NOT included. Keep/copy them in Voice with the exact names above.
Keep your existing artwork folders and saved browser data; game save key is unchanged.

VISUAL AND AUDIO FIXES
- Christmas tree is a floor-standing illustrated tree (christmas-tree.svg), clickable directly.
- Refrigerator is enlarged and lowered to stand on kitchen floor.
- Voice/here-i-am.m4a plays when DaisyBelle returns from school.
- Missing sound files are NOT included: copy pop-on-tap.m4a, objective-met.m4a, here-i-am.m4a into Voice exactly. Browser 404 means file was not found; check extension and location.
- favicon.ico 404 is harmless.
