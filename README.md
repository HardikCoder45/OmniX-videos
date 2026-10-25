# OmniX video production workspace

A prepared workspace for custom OmniX product launches, feature films, tutorials and social cutdowns. **Remotion is the main engine.** Product evidence, motion design, licensed assets, integration instructions and reusable briefs are organized here. Source repository and Desktop screenshot originals were preserved.

Read [AGENTS.md](AGENTS.md) for future-work instructions and [PRODUCTION_GUIDE.md](PRODUCTION_GUIDE.md) for the full production pipeline. Setup date: 8 October 2026.

## What is prepared

| Area | Actual contents |
| --- | --- |
| Product audit | 14 app dossiers, seven appendices, 206 granular feature/capture/motion entries |
| Source coverage | 1,408 permitted text files in the census; 293 route declarations, 99 tool entries, 1,108 UI-control occurrences, 58 desktop bridge methods |
| Screenshot evidence | 453 image records, 16 contact sheets, 272 relevant local symlinks, dated review/privacy notes |
| Downloaded asset library | 8,658 verified local files, about 255 MB, with provenance and license evidence |
| Existing OmniX media | 707 linked source files, including 624 Blender frames; historical/private reuse review required |
| Generated material | One inspected original raster plate plus an original eight-frame MotionFrame conversion study and atlases |
| Motion knowledge | 50 effect recipes, ten detailed original breakdowns, 42 concrete feature-film briefs |
| Effect studies | 18 installed HyperFrames components plus existing Shotcraft recipe/card/demo resources |
| Remotion runtime | Pinned 4.0.534 package family, local brand fonts, eight compositions including fixture and real narration integration checks, separate historical launch study |
| Integrations | Blender MCP connected; Higgsfield preset/idea role saved; ElevenLabs produced two local voice takes and real speech playback is integrated; actual readiness recorded |
| Supporting tools | Requested NullMotion and MotionFrame repositories pinned locally; official MotionFrame2.1.0 app installed and conversion tested |
| Verification | Two moving technical previews, 3D/portrait/square/historical stills, independent QA and local doctor report |

An inventory is not a current live product test. Each feature has an evidence class. Generated art, landing simulations and historical screenshots do not establish current product execution. LIVE COLAB rollout and experimental platform paths remain explicitly marked in the audit.

## Start working

From this directory:

```sh
npm run dev
npm run lint
npm run build
npm run doctor
```

`dev` opens the reusable Remotion studio. Root scripts dispatch into the actual projects; they do not start the product's backend. Render the technical sample:

```sh
cd /Users/hardikarora/Desktop/MAIN/OmniX-vids/projects/omnix-studio
npx remotion render MotionLab-Landscape ../../output/my-film/preview.mp4 --scale=0.5
```

The verified browser is installed Google Chrome with concurrency1, configured in both projects. Override the executable when moving computers. Package family versions are locked; newly installed Remotion skills become available to Codex on the next turn.

## Explore the asset library

Open [the searchable local catalog](assets/library/index.html). For reliable browser previews, start the localhost server:

```sh
npm run assets:serve
```

Then visit [OmniX asset catalog](http://127.0.0.1:8321/assets/library/index.html). If port8321 is already serving this workspace, reuse it. The catalog filters by search, category, pack and license and previews actual fonts, icons, images, audio and video. Models/HDRIs are labeled file links, not a claimed interactive 3D viewer.

| Category | Files | Use |
| --- | --- | --- |
| SVG icons | 8,371 | Lucide/Tabler labels, UI explanations and diagrams |
| Fonts | 35 across15 families | Brand/body/display/mono/Devanagari typography |
| Sound effects | 144 | Meaningful presses, moves, reveals and completion |
| Music | 4 | Licensed stock sound beds; audition before choosing |
| Models | 16 plus30 resources | glTF/GLB lighting and material studies |
| HDRIs | 10 | Studio/environment lighting |
| Texture maps | 34 | Twelve material sets |
| Stock videos | 3 | Abstract ink/bokeh/monochrome inserts |
| Remotion components | 11 | Cleared Shotcraft code assets |

See [asset operations](docs/workflows/ASSET_LIBRARY.md), [source/rights research](docs/research/ASSET_SOURCES.md), [full manifest](assets/library/manifest.json), [model credits register](assets/library/MODEL_CREDITS.md), and [generated provenance](assets/generated/manifest.json). This is a mixed-license library; stock files are not publicly redistributable as a standalone pack. Keep the local library and screenshot evidence private; copy only selected approved assets into portable film projects.

## Documentation map

### Product truth and capture

- [App index](docs/product/APP_INDEX.md): app roles, cross-app journeys and first film priorities.
- [Source audit](docs/product/SOURCE_AUDIT.md): coverage, extraction method and proof gaps.
- [Feature matrix](docs/product/FEATURE_MATRIX.md): each small feature's source, capture and motion idea.
- [Brand tokens](docs/product/BRAND_TOKENS.md): application/mobile/landing/video differences.
- [Screenshot audit](docs/product/SCREENSHOT_AUDIT.md): visual review, sheet index, feature mappings and privacy status.
- [Capture and privacy](docs/workflows/CAPTURE_AND_PRIVACY.md): current demo footage, safe fixtures and derivative review.

The app index links all14 dossiers and route/tool/control/bridge appendices. Source line links resolve on this computer; copy the permitted evidence summaries rather than private source files when sharing a brief.

### Motion design and film planning

- [Motion design system](docs/motion/MOTION_DESIGN_SYSTEM.md): pacing, readability, transitions, camera, material and sound.
- [Recipe atlas](docs/motion/RECIPE_ATLAS.md): 50 effects and ten original detailed breakdowns.
- [Feature-video playbook](docs/motion/FEATURE_VIDEO_PLAYBOOK.md): 42 audience-specific production briefs.
- [Machine-readable film briefs](docs/motion/feature-film-briefs.json).
- [Tools and reference research](docs/research/TOOLS_AND_REFERENCES.md): browser-inspected Dribbble reference, requested repos and primary-source web references.
- [Skills/capabilities](docs/research/SKILLS_AND_CAPABILITIES.md): installed instruction paths and operation boundaries.
- [Installed effect studies](motion-effects-library/README.md).

### Engines and connected tools

- [Readiness/status](docs/integrations/STATUS.md): installed versus connected versus rendered.
- [Remotion](docs/integrations/REMOTION.md).
- [Studio toolbox](docs/integrations/REMOTION_STUDIO_TOOLBOX.md): small browser/MCP operations for inspect, seek, guides, captions and background removal.
- [Higgsfield](docs/integrations/HIGGSFIELD.md).
- [Blender](docs/integrations/BLENDER.md).
- [ElevenLabs](docs/integrations/ELEVENLABS.md).
- [Voiceover handoff and test](docs/integrations/ELEVENLABS_REMOTION_HANDOFF.md).
- [Imagegen and Hairline](docs/integrations/IMAGEGEN_AND_HAIRLINE.md).
- [Reusable studio](projects/omnix-studio/README.md).
- [Historical launch study](projects/source-launch/README.md).

### Production operations and templates

- [Audio/captions](docs/workflows/AUDIO_AND_CAPTIONS.md).
- [Render/review](docs/workflows/RENDER_AND_QA.md).
- [Project brief](templates/briefs/PROJECT_BRIEF.md).
- [Storyboard](templates/briefs/STORYBOARD.md).
- [Capture manifest](templates/briefs/CAPTURE_MANIFEST.json).
- [Asset manifest](templates/briefs/ASSET_MANIFEST.json).
- [Audio cues](templates/briefs/AUDIO_CUES.json).
- [Delivery checklist](templates/briefs/DELIVERY_CHECKLIST.md).

## Checked outputs

[Workspace report](output/verification/WORKSPACE_REPORT.md) and [independent review](docs/QA_REVIEW.md) describe exact checks and limits. Technical samples:

- [Landscape motion lab](output/verification/motion-lab-landscape.mp4):10s,960×540,30fps.
- [Portrait motion lab](output/verification/motion-lab-portrait.mp4):10s,540×960,30fps.
- [Landscape contact sheet](output/verification/landscape-contact.png).
- [Portrait contact sheet](output/verification/portrait-contact.png).
- [Native Three material](output/verification/three-material.png).
- [Portrait feature starter](output/verification/feature-starter-portrait.png).
- [Square choreography](output/verification/motion-lab-square.png).
- [Historical source hook](output/verification/source-hook.png).

The original motion-lab exports are silent setup samples and scaffold placeholders, not a final commissioned launch film. The initial setup performed no paid provider generation. The later user-requested speech test is recorded separately. Higgsfield returned a free workspace with zero credits; the later ElevenLabs retry produced two successful voice takes, one account-gate failure and one rate-limited submission; actual speech is now integrated locally. Production npm audit is clear at the setup date; ten high findings remain in development tooling, documented in the report.

## Make the first film

Choose one brief from the playbook, create a project brief and record its current live proof with sanitized fixture content. Select the brand family and exact shot recipes, lock narration/sound, implement the shots in Remotion, review the moving preview and deliver the requested formats with source/credits/captions. Future work in this directory follows AGENTS.md and the evidence-backed production guide.

## Saved provider roles

Higgsfield supplies presets and video ideas; Remotion executes the master film; ElevenLabs supplies requested voiceover; two successful test takes are saved locally. See [workspace configuration](workspace.config.json), [idea card](templates/briefs/HIGGSFIELD_IDEA_CARD.md) and [audio integration check](output/verification/audio-integration-check.mp4).

The successful retry is recorded in [retry evidence](docs/integrations/elevenlabs-speech-retry.json). Preview the [real narration test](output/verification/elevenlabs-narration-check.mp4); its master audio is frozen under `projects/omnix-studio/public/audio/narration/`.

## OmniX Workflows film

The commissioned62-second Blender + Remotion pixel-workshop film is in [workflow/README.md](workflow/README.md). Its output folder contains the voiced captioned master, no-music version, clean version, measured SRT, cover and contact sheet. Native Blender sources, reusable GLBs, exact source sprites, story/spec, reference IDs and independent final review live with that isolated project. [Production instructions](workflow/AGENTS.md) document how to continue it.

## Custom Dynamic Workflows · 20 seconds

The separate vertical Blender launch film is in [workflow-dynamic-20/README.md](workflow-dynamic-20/README.md). It uses exact pixel-agent geometry, smooth perspective bridges, original restrained sound and the requested omnix.work closing URL. Final master, SFX-only version, cover, contact sheet, Blender source and editable Remotion timeline live in that project. Full-decode, all-frame blank checks and representative editor parity passed; its independent-review scope and account-limit interruption are recorded explicitly.

## OmniX Notch launch film · 76 seconds

The 1920×1080 / 60 fps launch film for the Dynamic Notch and desktop pet is in [omnix-notch-launch/README.md](omnix-notch-launch/README.md). It combines native Blender plates (MacBook awaken and finale, a 3D workflow constellation of the exact pixel agents) with a frame-driven Remotion copy of the product notch and pet, an ElevenLabs voice-over (Brian, with Jessica as Omni) and an original synthesized score. The master, a no-music version, SRT, cover, contact sheet and delivery checks are in `omnix-notch-launch/output/`.

## OmniX Desktop product demo · 130 seconds

The 1920×1080 / 60 fps feature demo of the desktop app, in the light default theme, is in [omnix-desktop-demo/README.md](omnix-desktop-demo/README.md). It covers the composer, slash commands and mentions, the plan, thinking and tools, code and terminals, multi-agent runs, Workflow Studio, custom agents, add-ons, model routing, browser and computer use, canvas and artifacts, routines, voice, the notch, pet and phone, and live re-theming. It is built from frame-driven copies of the product UI driven by the product's own theme engine, two Blender plates, an ElevenLabs voice-over (Brian and Jessica) and an original score with Mixkit SFX. The storyboard, with feature-evidence IDs, is `omnix-desktop-demo/docs/STORYBOARD.md`.
# OmniX-videos
# OmniX-videos
