# Changelog

## 10.0 — "Virtuoso"
Two promises: playing harder always pays, and a great build never makes the song safe.

**Dynamics pay**
- **Bounties**: the first time you restore a song at a new Dynamic, you get a one-time Echo bounty that grows with each step (a few hundred at *mp*, thousands at *silenzio*). Skipping ahead pays every step you skipped.
- **Pips**: each song card shows its nine Dynamics, from *p* to *∅*, lit up as you conquer them.
- **Prestige frames** on posters: bronze (*mp*, *mf*), silver (*f*, *ff*), gold (*fff*, *sfz*), a prism for *tutti* and silenzio black. Each carries a Dynamic badge.
- **Signature trails**: restore a song at *fortissimo* to wear its Signature. The nine are *Herald's Gold, Weeping, Lightweave, Hunger, Sleepwalk, Wake, Cinder, Hollow Light* and *Requiem*.
- **Virtuoso Crown**: restore a song at *silenzio* and it pays **+15% Echoes forever**. Your posters for that song carry the crown.
- New feats: *Virtuoso* (three songs at ff), *Maestro* (every song at ff), *Crowned*, *Third Movement* and *It Listens*.
- Existing saves keep their Dynamic progress, and any Signature trail already earned unlocks right away.

**The Hush listens**
- If Hushlings die the moment they appear, the Hush adapts: tougher Hushlings and more of them, up to ×3. It pays up to +50% more Echoes for the trouble, and eases off when you slow down. The HUD shows "LISTENING ×n".

**Bosses fight in movements**
- At two-thirds and one-third health, a Hush **holds its note**. It shrugs off damage for four bars while shaped Rest Marks fall and the song's Signatures join the fight, then it falters and you get a burst of Crescendo.
- A Hush can only lose so much health per second, so even a maxed build gets a real fight: at least about 24 seconds for a normal Hush and 45 for the final one. Weaker builds are unaffected.

**Finale**
- The last third of every song (from 7:00) brings shaped Rest Marks every four bars.

**Fixes**
- *Tempest* now actually grants the +50% experience and Echoes it promised.

## 8.0 — "Signatures"
Every song now feels like its own fight. Harder songs hit harder, mid-song Rest Marks take shapes, and a new song waits beyond Dream.

**Signature Hushlings**: one per song, found only there. Each gives a clear warning before it strikes and carries a name tag and health bar.
- **Gilded Herald** (Dawn): every two bars, fires a ring of golden notes with gaps to weave through.
- **Weeping Veil** (Dusk): fast and faint. It weeps sorrow pools on the path you're about to take; they slow and burn. It leaves one more when it falls.
- **Lightweavers** (Aurora): a pair that circles you with a curtain of light strung between them. It flickers for half a bar, then burns for a full bar.
- **The Maw** (Abyss): a slow, vast hunger that drags you in and inhales hard every fourth bar.
- **Somnambulist** (Dream): marks where you're heading, then steps out of the dream onto that spot.
- **Leviathan** (Tide): sights you down a long channel, tracks you for a moment, then locks on and charges through.
- **Bellows** (Ember): draws breath, tracks you, then exhales a cone of fire on the downbeat.
- **Hollow Lantern** (Hallow): its dirge whips nearby Hushlings into a frenzy and calls up more.

They arrive sooner, and more often, on harder songs. More can be alive at once as the song goes on and in Endless, and later ones can be elite. Silencing one pays bonus Echoes.

**Requiem**: a new song in Locrian, the darkest musical mode. It's the hardest song yet (difficulty 2.6, Echoes ×3.8) and every Signature appears there. It unlocks once you've restored Dream.

**Shaped Silence**: mid-song (sooner on harder songs) and during boss fights, Rest Marks take shapes:
- **Lines** and **crosses** across the arena. Step aside.
- **Chords**: one mark on you and three around you.
- **Fermata**: a ring where the only safe place is the still eye in the middle. For once, hold still.

**Harder songs hit harder**
- Hushling contact damage now scales with song difficulty (Dawn ×1.0 up to Requiem ×1.48). Before, harder songs only made Hushlings tougher, not more dangerous.
- Rest Marks start earlier, ramp faster and hit harder on harder songs.

**New feats**: *Signature*, *Every Voice of Silence* (silence all eight), *Requiem* and *Eye of the Storm* (survive a Fermata). The Songbook gains entries for all eight Signatures, and How to Play explains them.

## 7.0 — "Nocturne"
The Hush fights back. A first run on fresh data reached level 120 and 20 minutes of Endless without moving or using Crescendo. That can't happen anymore: standing still is now the most dangerous thing you can do.

**Rest Marks**
- From 1:30, the Hush aims at where you stand. A red ring fills over one bar and lands on the downbeat for a share of your **max health**, so no build can simply out-tank it.
- They come every 4 bars, then every 2 after 4:00, then every bar in pairs after 7:00 (one aimed at where you are, one at where you're heading). Endless and boss fights add more.
- **Riposte**: dash through a mark right on the beat to answer with a shockwave, Crescendo charge and a flash.
- A one-time banner on the first mark of each run teaches the rule: keep moving.

**New threats**
- **Cantor** (from 5:00): a distant sniper that keeps 380–460 away, paints a red sight line, then fires one fast note on the downbeat. Step off the line.
- **Marks of Silence** (Endless): every two minutes a permanent curse joins the song. The eight curses are *Echoing Rests, Leaden, Hunger, Choir of Hush, Glass Bones, Eclipse, Quickening* and *Barrage*. They show in the HUD and the pause screen.
- **Endless bites**: every hit deals at least 5% of max health, rising by 0.8% each minute of the encore.

**New picks**
- Motif **Anticipation**: Rest Marks warn you half a bar earlier, and dodging one heals.
- Motif **Sidestep**: dodging a mark gives a burst of speed and Crescendo.
- Dissonance **Tempest**: twice the Rest Marks for +50% experience and Echoes.

**Progression**
- Experience needed climbs faster past level 70.
- New feats: *Riposte*, *Dancer* (50 dodges in a song), *Standing Ovation* (10 minutes of Endless), *Marked* (survive four curses).
- New Concert Hall record: **Longest Encore**.
- Songbook entries for Cantors and Rest Marks, plus a How to Play section.

**Testing**
- Every balance pass now includes a player who stands still and a "fortress" player who only Rest Marks can hurt. The fortress player falls about 45 seconds after the marks begin. Moving autopilots restore the song but fall 4–7 minutes into Endless.

## 6.0 — "Encore"
More life, more juice, more surprises — and a full code scrub.

**A living song**
- **Champions** — named elites like *Vesper the Tuneless* or *Grimtone of the Broken Key*, each with three powers: *Swift, Bulwark, Veiled, Splitting, Vampiric, Haunting, Volatile, Blinking*. Name tag and health bar; every one carries a music box. Ordinary elites can carry a power too.
- **Moments** — every couple of minutes something happens: an **Accelerando** (the whole song surges +30 BPM with +50% experience, then a Ritardando), a **Note Rain** of falling light, or a **Champion Duel**.
- **Music that breathes** — drum fills every 8 bars, a breakdown every 32 where the drums drop out and crash back in.
- **Ambient life** — bats over Hallow, embers in Ember and Abyss, bubbles in the Tide, petals on Dusk and Aurora, fireflies at Dawn and in Dream.

**New voices**
- **Harp ≡** — fans of piercing strings the way you face, on the off-beats.
- **Organ ▥** — pillars of sound that erupt beneath clusters of Hushlings.
- New Duets: **Cascade** (Harp + Arpeggio) and **Cathedral** (Organ + Crash). Ten Duets in all.
- New Singers: **Iris, the Harp** (Solo: *Cloudburst*) and **Odette, the Organ** (Solo: *Toccata*).

**Juice**
- Tiny notes fly from silenced Hushlings, the screen edges pulse with the beat (stronger as harmony climbs), PERFECT dashes freeze time for a heartbeat, light rays burst on level-ups, boss and Champion kills, and your trail doubles at high harmony.

**Daily gifts**
- A seven-day gift calendar on the title screen; keep the streak for a big seventh-day gift.

**Code scrub** (independent audit; every finding fixed and re-verified)
- Fixed a crash that lost Echoes when buying a Familiar after a progress reset.
- Fixed the *Song Restored* screen being skipped if a level-up or music box was open when The Great Silence fell.
- End-of-run timers can no longer leak into your next song.
- Studio runs no longer count toward unlocks, records or stats; Immortal really is immortal.
- Recital, Studio and Score movements now truly start at their higher level (no more "LEVEL −7"), so level-scaled abilities scale properly.
- Leaving a results screen for The Score no longer keeps the old song's HUD alive.
- Crescendo and Pause now respond while another finger is steering (iPhone).
- The music now stops when the app goes to the background, and resumes cleanly.
- Nightfall's darkness returns after a Silence Storm.
- Corrupted saved song/singer choices are repaired on load; the offline cache can no longer store an error page.
- Smoother frames: floating text no longer uses expensive blur, fewer per-frame DOM writes.

**Balance**
- Endless ramps harder to account for the extra power in 6.0.
- Five new feats.

## 5.1 — Balance
Tuned from a real first playthrough, which became unkillable by 9:00, stopped leveling at 47 and nearly maxed Resonance in one run.

- **Fixed: leveling could stall.** Once 420 pickups were scattered across the field, new light merged into far-off pickups you'd never reach. Light now merges into the nearest pickup, drifts to you after 25 seconds (sooner when the field is crowded), and is never stranded.
- **Builds have limits:** a song now holds at most **6 Motifs** and **3 Dissonances**. Music boxes are rarer (11% from elites, +3% per Fortune), stop dropping once your build is full, and let you **keep the box closed** instead of taking a Dissonance.
- **Overflow:** once every voice and harmony is maxed, level-ups grant +1% damage (up to +30%) instead of Echoes.
- **Endless bites back:** after the song is restored, Hushlings grow far tougher and hit harder every minute, and elites become common. Expect Endless to end you somewhere past the quarter-hour.
- Leveling slows after level 45.
- **Echo economy:** Echoes from kills now grow with the square root of kills, time past 10:00 counts for less, and Hallow pays ×1.5 (was ×2). Resonance costs ×2.5; Singers, trails and Familiars cost ×2. A strong 10-minute song earns roughly 800–1,500 Echoes, so maxing Resonance is a long road.
- Harmony's score multiplier caps at ×500 combo.
- The pause screen shows how full your Motif and Dissonance slots are.

## 5.0 — "Opus"
An update big enough to skip a number.

**Living songs**
- **Tide** (melodic minor · oceanic) — every few bars a current sweeps the whole field, carrying Hushlings, dark notes, light and you. Unlocks at 20 stars in The Score.
- **Ember** (Mixolydian · fierce) — fires break out around you every two bars. They scorch the Hush far worse than you; lure them in. Unlocks after restoring the song three times.
- Both have their own composed themes, palettes and Dynamics ladders.

**Seasonal events**
- A new event calendar. **Hallow's Hush** (Oct 20 – Nov 7) opens the **Hallow** song (harmonic minor), puts lantern faces on the Hushlings, doubles Golden Note rewards, and brings an event trail (*Jack-o'-Light*), an event Familiar (*Jack*) and two event feats.
- **Silent Night** (Dec 15 – Jan 5): snow on every song and +25% Echoes.

**Familiars**
- Seven companions that follow you into every song: *Metronome Finch, Lantern Moth, Little Bell, Hymn Shell, Firefly, Mockingbird* and the event-only *Jack*. Bring one from Resonance.

**Dissonances**
- Eight risk-and-reward gifts that sometimes appear in music boxes: *Brittle Glass, Frenzy, Greed, Overdrive, Deafened, Swarm Song, Requiem, Presto*. Restore the song holding three for a feat.

**Modes**
- **Recital** — every form of the Hush back to back, ending with The Great Silence. Starts at level 10. Fastest time recorded.
- **Weekly Concert** — a seeded week-long challenge: one Singer, one Song, three twists, double Echoes.
- **Studio** — set the tempo, crowd, toughness, starting level, give yourself the full band, or turn on immortality and just listen.
- Four new twists for the Daily Hum and Weekly Concert: *Giants, Nightfall, Golden Age, Maestro*.

**Memory**
- **Concert Hall** — your last 25 songs with their shapes, and personal records (longest song, fastest restore, fastest Recital, best harmony, PERFECT streak, most silenced).
- **Posters** — turn any finished song into a shareable image.
- **Fragments of the old song** — twenty pieces of HUSH's story, found as you play, kept in the Songbook.

**Phones**
- Left-handed buttons, larger buttons, and a battery saver (lower resolution, 30 fps).

- 14 new feats (64 total). Songbook now covers Dissonances, Familiars and Fragments.

## 3.0 — "Symphony"

**The Score — a 20-movement campaign**
- Four acts — *Overture* (Dawn), *Adagio* (Dusk), *Scherzo* (Aurora), *Finale* (Dream) — of short, handcrafted movements, each with its own goal and rules: survive the dark with only moths for company, shatter a crystal garden, answer the Hush's calls, outlast leeches, reach *tutti*, and finally face The Great Silence.
- Every movement has three stars (clear it, plus two challenges like *take no damage* or *land 20 PERFECTs*). 60 stars in all; acts open at 8, 18 and 30 stars. New stars pay Echoes.
- Complete it for the **Staff Lines** trail and three new feats.

**Singer Solos**
- Every Singer's Crescendo now ends in a signature **Solo**: Radiance (heal), Earthshaker (stun), Starfall, Hallelujah, Thunderstorm, Singularity (a black hole that detonates), Tidal Sweep, Ribbon Dance, Grand Crash, Remembrance. Listed on each Singer's card and in the Songbook.

**Call & Response**
- A new rhythm event: the song plays a phrase on golden beats — dash on exactly those beats in the next bar to answer and earn a music box.

**New Hushlings & hazards**
- **Phantoms** only exist on the beat — between beats they can't be hit (and can't hurt you).
- **Leeches** latch onto your light and drain it until you dash them off.
- **Resonant Crystals** ring out when shattered, blasting everything nearby — chain them.
- **Silence Zones** open on the field late in a song; inside one, your voices fall silent.

**Music**
- Every Song now has its own composed **theme**, sung by a lead voice between the action (and on the title screen).

**Also**
- High-contrast Hushlings option for readability.
- Title screen reorganized around The Score; Daily Hum and Verses side by side.
- Six more feats (50 total). Robustness fixes.

## 2.0 — "Fortissimo"
The biggest update yet: an ending, a reason to come back every day, and a long road to mastery.

**An ending worth earning**
- **The Great Silence** — a final Hush arrives at 9:00. At two-thirds health *the lights go out* and only your own light (and your music) cuts the dark; at one-third it holds nothing back. Silence it to **restore the song**, then keep singing in Endless or take a bow. In Endless it returns every fourth Hush.
- **Silence Storms** — at 7:00 the world goes dark for 26 seconds and moths flood in. Stay close to your light.

**Motifs & music boxes**
- Elite Hushlings (30%) and every Hush drop a glowing **music box**. Walk into it to choose one of three **Motifs** — 16 rule-bending gifts: *Metronome, Staccato, Sforzando, Fermata, Coda, Cadence, Tremolo, Grace Note, Key Signature, Rubato, Hymnal, Encore Seal, Overture, Dynamo, Resolution, Vibrato*. Edge-of-screen arrows point to boxes you haven't opened.

**New voices, Duets & Singers**
- **Legato ⌒** — your path leaves a burning ribbon of sound (and a string section that swells when you move).
- **Crash ✲** — a cymbal crash that stuns every Hushling nearby and shatters dark notes.
- New Duets: **Silk Road** (Legato + Drone) and **Fortissimo** (Crash + Thump). Six Duets in all.
- New Singers: **Liora, the Thread** (Legato) and **Tamsin, the Bell** (Crash).

**New Hushlings**
- **Moths** weave toward you in flocks of six.
- **Conductors** hang back and drive every Hushling around them 35% faster. Silence them first.

**Come back louder**
- **Dynamics** — restore a song to unlock the next of nine difficulty levels for it, from *p* to *∅ silenzio*, each adding a twist and +30% Echoes.
- **Daily Verses** — three fresh challenges every day with Echo rewards.
- **Singer Mastery** — each Singer grows stronger the more you sing with them (up to Mastery 10, +13.5% damage).
- **Wardrobe** — ten light trails: Ember, Ink, Little Notes, Petals, Prism, Comet, and three earned ones (Aurora, Gilded, Hollow).
- **Resonance, tier two** — higher caps on core upgrades plus *Fortune, Quick Feet, Prelude* (start with a Motif) and *Golden Hour*.
- Economy rebalanced so progress lasts: Echoes from kills reduced; many new things to spend them on.

**Juice**
- **Harmony tiers** — combos climb through *piano → mezzo → forte → fortissimo → tutti*: the drums thicken, bells and cymbals join, the sky glows brighter.
- Cinematic letterbox when a Hush arrives, camera punch on big moments, enemies squash when struck, elite kills hit-stop, a heartbeat when you're low, a shockwave that clears space when you finish leveling up.
- Pause now shows your full build.

**Mobile**
- Touch-first guide, iPhone silent-switch hint, vibration setting only where supported, tighter layouts for 360-pt Android screens, no double-tap zoom.
- 17 new feats (41 total). Songbook now covers Motifs and every new Hushling.

## 1.2 — "The Groove"
- **Dash on the beat »**: a new DASH button (or Shift / J / a second-finger tap). Dash right on the beat for a **PERFECT** — a shockwave, a breath of invulnerability and extra Crescendo. A shrinking **beat-guide ring** around your light shows exactly when. Chain perfects for streaks.
- **Duets ✶**: max out two partner voices and they can merge into a Duet, a new stronger form:
  - *Constellation* (Pulse + Arpeggio) — bolts shatter into homing sparks
  - *Subterranean* (Thump + Drone) — a vast drone that Thump drags foes into
  - *Thunderhead* (Snare Arc + Echo) — echo notes burst into chain lightning
  - *Galaxy* (Chorus + Glissando) — more, harder-hitting notes that swell on the beat; beams erase dark notes
- **Two new bosses**: the Hush now takes three forms in turn — *The Hush*, *The Stillness* (spirals, then vanishes and reappears beside you) and *The Last Rest* (aimed fans, summons Veils).
- **New Song — Aurora** (Dorian · nostalgic): green-and-teal skies, unlocked by defeating the Hush three times.
- **Songbook ❦**: a collection of every voice, Duet, harmony and Hushling you've met. Undiscovered Duets hint at their partners.
- **Daily streaks ☼**: play the Daily Hum on consecutive days for up to +70 bonus Echoes. Your streak shows on the title screen.
- **Share your song ⧉**: a one-tap summary of your run — time, harmony, a little waveform of how it went, your lineup and a link.
- End screen now tracks Perfects, best Perfect streak and Duets.
- Settings: beat-guide toggle and a **timing offset** slider for Bluetooth audio latency.
- Five new feats (24 total). Settings moved to the ⚙ in the title corner.

## 1.1 — "A New Verse"
- **App icon & installable app**: a new icon, a web app manifest, an Apple touch icon and a service worker. *Add to Home Screen* now gives you a fullscreen HUSH that plays offline.
- **New voice — Glissando ∿**: a beam of sound that sweeps around you once per bar, with a gliding tone in the soundtrack. Up to three beams.
- **New Singer — Kael, the Wave**: begins with Glissando. +8% speed, +10% area.
- **New Hushling — the Veil ⬡**: shielded in silence except on beats 2 and 4. Strike in the gaps.
- **Golden Notes ✪**: a rare, fleeing golden Hushling. Catch it before it slips away for a free harmony and +25 Echoes. An edge-of-screen arrow points the way.
- **The shape of your song**: the end screen draws your run as a waveform, plus the lineup of voices that made it.
- **Vibration** on hits, crescendos and boss kills (toggle in Settings, where supported).
- The screen stays awake while you play.
- Two new feats: *Golden Ear* and *Through the Veil*.
- Polish: softer boss hit-flash, clearer enemy projectiles, better font fallbacks, tidier HUD on small phones, faster early light pickup, floating labels no longer overlap.

## 1.0 — First Song
- Initial release.
