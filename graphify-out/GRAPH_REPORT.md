# Graph Report - GymMane  (2026-10-15)

## Corpus Check
- Large corpus: 1399 files · ~4,356,477 words. Semantic extraction will be expensive (many Claude tokens). Consider running on a subfolder.

## Summary
- 28895 nodes · 32378 edges · 126 communities (109 shown, 17 thin omitted)
- Extraction: 100% EXTRACTED · 0% INFERRED · 0% AMBIGUOUS · INFERRED: 11 edges (avg confidence: 0.85)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- Localization Hub
- Strings: AR
- Strings: DE
- Strings: EN
- Strings: ES
- Strings: FA
- Strings: FR
- Strings: IT
- Strings: JA
- Strings: KO
- Strings: NL
- Strings: PL
- Strings: PT
- Strings: RU
- Strings: TR
- Strings: UK
- Strings: ZH
- Exercise & Routine Screens
- Fit & Nutrition State
- Food Logging Screens
- Shared UI Widgets
- Workout Session State
- Platform Services Bridge
- Workout Import
- Stateful Widget Base
- Settings State
- Live Session Screen
- Tools State
- Nutrition Models
- Exercise Animations
- FitCore State Root
- Stats State
- App Shell & Navigation
- Sticker Cutout Service
- Profile & Timeline Screens
- Wear OS Shell
- Dialogs & Start Sheet
- Plan Sharing
- Beeper, Radar & Steps
- Settings Screen & Main
- AI Plan & Import Sheets
- Nutrition Cards
- Nutrition Art
- Liquid Notch Toasts
- Progress Screen
- Regression Tests (State)
- Charts & Painters
- Ruler & Timer Pickers
- Notes & Measures Models
- Entrance Animations
- Exercise Library State
- Note Media Kit
- L10n Wrapper & Catalogs
- App Root & Exercises
- Reminder Notifications
- UI Behavior Tests
- Backup Zip
- Sticker Screen
- Glass Surfaces
- Meal Editor
- Exercise Media Preview
- Medal Rendering
- Routines State
- Award Celebrations
- Home Widgets & Share Cards
- Cutout Editor
- Meal Plans
- Workout Models
- Exercise Name Matching
- Backup Tests
- Body Map Art
- Android Themed Widgets
- Food Library
- Onboarding
- Rest Alarm
- SVG Icons
- Catalog & Alias Tests
- Live Session Model
- App Colors
- SQLite Reader
- Meal Prep Batches
- Notes State
- Session & Export Tests
- Import Tests
- Android MainActivity
- Timeline State
- Program Templates
- Gym Places State
- Stats & Profile Tests
- Exercise Model
- Android Live Notifier
- Wear & Swap Tests
- Health Connect Bridge
- Measures State
- Exercise Catalog
- FIT File Export
- Tool Art
- Medal Looks
- Localizations Delegate
- Steps State
- Awards State
- Profile Model
- Moments State
- State Mixins
- Exercise Aliases
- App Theme
- Progress Shot Model
- Settings Water Widget
- Place Model
- Persistence Tests
- Heatmap Widget
- Body Widget
- Stats Widget
- Glass Dialog Route
- ARB Tidy Script
- Level-Up Test
- Test Hooks
- Liquid Notch Frame
- Chinese Locales
- Import Format Enum

## God Nodes (most connected - your core abstractions)
1. `AppLocalizations` - 23 edges
2. `GymColors` - 18 edges
3. `_` - 16 edges
4. `FitState` - 16 edges
5. `MainActivity` - 13 edges
6. `LiveNotifier` - 11 edges
7. `HealthBridge` - 9 edges
8. `bindThemedImage()` - 8 edges
9. `DayWidgetProvider` - 8 edges
10. `OutcomeReceiver` - 6 edges

## Surprising Connections (you probably didn't know these)
- `AppLocalizationsAr` --inherits--> `AppLocalizations`  [EXTRACTED]
  lib/l10n/app_localizations_ar.dart → lib/l10n/app_localizations.dart
- `AppLocalizationsDe` --inherits--> `AppLocalizations`  [EXTRACTED]
  lib/l10n/app_localizations_de.dart → lib/l10n/app_localizations.dart
- `AppLocalizationsEn` --inherits--> `AppLocalizations`  [EXTRACTED]
  lib/l10n/app_localizations_en.dart → lib/l10n/app_localizations.dart
- `AppLocalizationsEs` --inherits--> `AppLocalizations`  [EXTRACTED]
  lib/l10n/app_localizations_es.dart → lib/l10n/app_localizations.dart
- `AppLocalizationsFa` --inherits--> `AppLocalizations`  [EXTRACTED]
  lib/l10n/app_localizations_fa.dart → lib/l10n/app_localizations.dart

## Import Cycles
- None detected.

## Communities (126 total, 17 thin omitted)

### Community 0 - "Localization Hub"
Cohesion: 0.00
Nodes (1373): about, aboutBlurb, aboutGymmane, actActive, activityLabel, activityLevel, actLight, actModerate (+1365 more)

### Community 1 - "Strings: AR"
Cohesion: 0.00
Nodes (1365): about, aboutBlurb, aboutGymmane, actActive, activityLabel, activityLevel, actLight, actModerate (+1357 more)

### Community 2 - "Strings: DE"
Cohesion: 0.00
Nodes (1365): about, aboutBlurb, aboutGymmane, actActive, activityLabel, activityLevel, actLight, actModerate (+1357 more)

### Community 3 - "Strings: EN"
Cohesion: 0.00
Nodes (1365): about, aboutBlurb, aboutGymmane, actActive, activityLabel, activityLevel, actLight, actModerate (+1357 more)

### Community 4 - "Strings: ES"
Cohesion: 0.00
Nodes (1365): about, aboutBlurb, aboutGymmane, actActive, activityLabel, activityLevel, actLight, actModerate (+1357 more)

### Community 5 - "Strings: FA"
Cohesion: 0.00
Nodes (1365): about, aboutBlurb, aboutGymmane, actActive, activityLabel, activityLevel, actLight, actModerate (+1357 more)

### Community 6 - "Strings: FR"
Cohesion: 0.00
Nodes (1365): about, aboutBlurb, aboutGymmane, actActive, activityLabel, activityLevel, actLight, actModerate (+1357 more)

### Community 7 - "Strings: IT"
Cohesion: 0.00
Nodes (1365): about, aboutBlurb, aboutGymmane, actActive, activityLabel, activityLevel, actLight, actModerate (+1357 more)

### Community 8 - "Strings: JA"
Cohesion: 0.00
Nodes (1365): about, aboutBlurb, aboutGymmane, actActive, activityLabel, activityLevel, actLight, actModerate (+1357 more)

### Community 9 - "Strings: KO"
Cohesion: 0.00
Nodes (1365): about, aboutBlurb, aboutGymmane, actActive, activityLabel, activityLevel, actLight, actModerate (+1357 more)

### Community 10 - "Strings: NL"
Cohesion: 0.00
Nodes (1365): about, aboutBlurb, aboutGymmane, actActive, activityLabel, activityLevel, actLight, actModerate (+1357 more)

### Community 11 - "Strings: PL"
Cohesion: 0.00
Nodes (1365): about, aboutBlurb, aboutGymmane, actActive, activityLabel, activityLevel, actLight, actModerate (+1357 more)

### Community 12 - "Strings: PT"
Cohesion: 0.00
Nodes (1365): about, aboutBlurb, aboutGymmane, actActive, activityLabel, activityLevel, actLight, actModerate (+1357 more)

### Community 13 - "Strings: RU"
Cohesion: 0.00
Nodes (1365): about, aboutBlurb, aboutGymmane, actActive, activityLabel, activityLevel, actLight, actModerate (+1357 more)

### Community 14 - "Strings: TR"
Cohesion: 0.00
Nodes (1365): about, aboutBlurb, aboutGymmane, actActive, activityLabel, activityLevel, actLight, actModerate (+1357 more)

### Community 15 - "Strings: UK"
Cohesion: 0.00
Nodes (1365): about, aboutBlurb, aboutGymmane, actActive, activityLabel, activityLevel, actLight, actModerate (+1357 more)

### Community 16 - "Strings: ZH"
Cohesion: 0.00
Nodes (1365): about, aboutBlurb, aboutGymmane, actActive, activityLabel, activityLevel, actLight, actModerate (+1357 more)

### Community 17 - "Exercise & Routine Screens"
Cohesion: 0.01
Nodes (195): awardLine, awardName, medalAsset, medalOffAsset, medalSpinAsset, AboutScreen, build, _credits (+187 more)

### Community 18 - "Fit & Nutrition State"
Cohesion: 0.01
Nodes (209): activeBatches, activeGoals, addBurned, addMealSlot, addPlanItem, addSupplement, addWater, backFromNutrition (+201 more)

### Community 19 - "Food Logging Screens"
Cohesion: 0.02
Nodes (170): _AddFoodSheet, _AddFoodSheetState, _AmountDial, approx, asShake, _base, _c, _cat (+162 more)

### Community 20 - "Shared UI Widgets"
Cohesion: 0.01
Nodes (162): _ChartCard, _DetailGrid, _FatTypesCard, _HeroCard, _QualityCard, _RingCard, _ShakeTile, _SplitBar (+154 more)

### Community 21 - "Workout Session State"
Cohesion: 0.01
Nodes (157): addExerciseToSession, addSet, addWarmupSets, _advanceChain, advanceDelay, _advanceTimer, _advanceWhenDone, _armRest (+149 more)

### Community 22 - "Platform Services Bridge"
Cohesion: 0.02
Nodes (96): AlarmStore, audioExtensions, clear, _dir, _ext, importSound, init, maxDuration (+88 more)

### Community 23 - "Workout Import"
Cohesion: 0.02
Nodes (109): _anyWeight, archive, _backupOf, best, cell, clock, cols, custom (+101 more)

### Community 24 - "Stateful Widget Base"
Cohesion: 0.03
Nodes (103): _FoodEditor, _FoodEditorState, _StickerDrafts, _SupplementEditor, _SupplementEditorState, AppShell, _AppShellState, _LiquidPill (+95 more)

### Community 25 - "Settings State"
Cohesion: 0.02
Nodes (107): _adoptDeviceLanguage, alarmAllowed, alarmAskedAt, alarmSound, alarmSoundName, alarmSoundPath, alarmStyle, _applyLanguage (+99 more)

### Community 26 - "Live Session Screen"
Cohesion: 0.02
Nodes (101): active, _addRow, all, already, _announce, _asksEffort, autoMoves, away (+93 more)

### Community 27 - "Tools State"
Cohesion: 0.02
Nodes (100): activeToolId, backFromTools, barFor, barOptions, bfHeight, bfHip, bfNeck, bfSex (+92 more)

### Community 28 - "Nutrition Models"
Cohesion: 0.02
Nodes (97): _addAmino, Amino, aminoProtein, aminoScores, animal, approx, assetOfPhoto, at (+89 more)

### Community 29 - "Exercise Animations"
Cohesion: 0.02
Nodes (87): anim, _Bit, _bits, build, _c, celebrate, color, colors (+79 more)

### Community 30 - "FitCore State Root"
Cohesion: 0.02
Nodes (96): 4, archived, autoWarmup, backFromPreferences, bodyweight, checkins, customExercises, _dayKey (+88 more)

### Community 31 - "Stats State"
Cohesion: 0.02
Nodes (97): addBodyweight, addLoggedSet, athleteLevel, averageSession, bestRepsSeries, bestWorkoutLabel, bodyweightHistory, bodyWindowDays (+89 more)

### Community 32 - "App Shell & Navigation"
Cohesion: 0.02
Nodes (64): _animatedScreen, _awardWait, _blurTop, build, _celebratedOne, _celebrating, _changedUnder, _closeCelebration (+56 more)

### Community 33 - "Sticker Cutout Service"
Cohesion: 0.02
Nodes (94): a, alpha, any, area, auto, best, bg, big (+86 more)

### Community 34 - "Profile & Timeline Screens"
Cohesion: 0.02
Nodes (79): build, CompareScreen, _picker, _shot, _add, animation, _bucket, build (+71 more)

### Community 35 - "Wear OS Shell"
Cohesion: 0.02
Nodes (87): _active, _arm, attach, _back, build, _canDim, _cap, _channel (+79 more)

### Community 36 - "Dialogs & Start Sheet"
Cohesion: 0.03
Nodes (63): Routine, SetKind, build, day, _go, _label, _option, _plannedCard (+55 more)

### Community 37 - "Plan Sharing"
Cohesion: 0.02
Nodes (86): 0, addRoutine, addRoutines, body, _candidates, cell, clock, col (+78 more)

### Community 38 - "Beeper, Radar & Steps"
Cohesion: 0.02
Nodes (72): Beeper, _chime, chimeOn, chimeWav, _context, _failed, _go, _hold (+64 more)

### Community 39 - "Settings Screen & Main"
Cohesion: 0.02
Nodes (65): init, initializeDateFormatting, live, main, _onWatch, _sessionSideEffects, watch, _act (+57 more)

### Community 40 - "AI Plan & Import Sheets"
Cohesion: 0.03
Nodes (64): _added, _answer, build, _chip, _copy, createState, dispose, _export (+56 more)

### Community 41 - "Nutrition Cards"
Cohesion: 0.03
Nodes (74): aminoName, _aminoShort, at, chart, _clock, _customWater, _date, _dayTone (+66 more)

### Community 42 - "Nutrition Art"
Cohesion: 0.03
Nodes (71): animate, asset, bottom, build, CalorieRing, carbs, child, color (+63 more)

### Community 43 - "Liquid Notch Toasts"
Cohesion: 0.03
Nodes (61): accent, action, build, cap, child, complete, _controller, createState (+53 more)

### Community 44 - "Progress Screen"
Cohesion: 0.03
Nodes (68): _all, bg, _blocks, _body, build, _chart, color, _confirmDelete (+60 more)

### Community 45 - "Regression Tests (State)"
Cohesion: 0.05
Nodes (47): main, main, main, routine, log, main, killAndReopen, main (+39 more)

### Community 46 - "Charts & Painters"
Cohesion: 0.03
Nodes (67): _AminoRadar, _TrackPainter, _Checker, _RingPainter, _ConfettiPainter, BodyPainter, a, accent (+59 more)

### Community 47 - "Ruler & Timer Pickers"
Cohesion: 0.03
Nodes (61): allowImplicitScrolling, applyTo, askRuler, axis, build, color, _count, createBallisticSimulation (+53 more)

### Community 48 - "Notes & Measures Models"
Cohesion: 0.03
Nodes (57): bodyBaseLite, bodyBaseMain, bodyViewH, bodyViewW, muscleFills, muscleHits, BodyMeasure, date (+49 more)

### Community 49 - "Entrance Animations"
Cohesion: 0.03
Nodes (58): _animate, animates, build, _c, child, createState, _decide, _delay (+50 more)

### Community 50 - "Exercise Library State"
Cohesion: 0.03
Nodes (63): activeExercise, activeExerciseId, activeExerciseSteps, addCustomExercise, allExercises, attachExerciseMedia, _builtInExercises, _bullet (+55 more)

### Community 51 - "Note Media Kit"
Cohesion: 0.03
Nodes (60): _arrow, badge, build, _c, _cell, color, compact, counts (+52 more)

### Community 52 - "L10n Wrapper & Catalogs"
Cohesion: 0.03
Nodes (56): 1, activityName, appLanguage, appLanguages, base, bmiCategory, build, _capitalize (+48 more)

### Community 53 - "App Root & Exercises"
Cohesion: 0.03
Nodes (54): build, _ButtonNavScrim, child, createState, dispose, GymManeApp, _GymManeAppState, initState (+46 more)

### Community 54 - "Reminder Notifications"
Cohesion: 0.04
Nodes (44): _android, cancel, _darwin, enabled, _id, instance, _plugin, ProgressReminder (+36 more)

### Community 55 - "UI Behavior Tests"
Cohesion: 0.04
Nodes (28): addNotes, _exId, _host, main, tapVisible, logWorkouts, main, main (+20 more)

### Community 56 - "Backup Zip"
Cohesion: 0.04
Nodes (50): alarm, alarmBase, _alarmDir, alarmName, alarmPath, archive, base, buffer (+42 more)

### Community 57 - "Sticker Screen"
Cohesion: 0.04
Nodes (51): b, _base, _best, build, _busy, _canvas, _chip, color (+43 more)

### Community 58 - "Glass Surfaces"
Cohesion: 0.04
Nodes (47): animation, blur, _BlurBarrier, blurFull, blurOff, build, buildModalBarrier, buildTransitions (+39 more)

### Community 59 - "Meal Editor"
Cohesion: 0.04
Nodes (51): _DishEditor, _DishEditorState, entries, _EntryList, _EntryRow, _factor, _Folders, _FoodShelf (+43 more)

### Community 60 - "Exercise Media Preview"
Cohesion: 0.04
Nodes (42): bordered, build, _c, child, createState, dispose, ex, ExerciseMedia (+34 more)

### Community 61 - "Medal Rendering"
Cohesion: 0.04
Nodes (47): _back, _backImage, build, canvas, _clickAtFace, createState, dispose, endRecording (+39 more)

### Community 62 - "Routines State"
Cohesion: 0.04
Nodes (50): activeRoutine, activeRoutineId, addToRoutineAndEdit, assignRoutineToDay, backFromAiPlan, backFromRoutines, bumpRoutineSets, chainsToNext (+42 more)

### Community 63 - "Award Celebrations"
Cohesion: 0.04
Nodes (45): AwardId, at, avatar, _Bit, _bits, build, _cardKey, color (+37 more)

### Community 64 - "Home Widgets & Share Cards"
Cohesion: 0.04
Nodes (42): GymColors, BodyWidgetView, build, _card, _chip, days, done, dot (+34 more)

### Community 65 - "Cutout Editor"
Cohesion: 0.04
Nodes (46): CutoutDraft, _box, _brush, _brushes, _brushPx, build, _busy, createState (+38 more)

### Community 66 - "Meal Plans"
Cohesion: 0.04
Nodes (46): context, _daysLine, empty, importMealPlanFile, _isNew, _item, join, _logToday (+38 more)

### Community 67 - "Workout Models"
Cohesion: 0.05
Nodes (41): BodyweightEntry, chained, color, copyWith, counts, date, durationSec, exerciseIds (+33 more)

### Community 68 - "Exercise Name Matching"
Cohesion: 0.05
Nodes (39): alias, _aliasIndex, ce, cMeaning, _equipment, exact, exactExtra, ExerciseFilter (+31 more)

### Community 69 - "Backup Tests"
Cohesion: 0.06
Nodes (26): docs, main, sourceSound, bench, main, mp4, png, pushUp (+18 more)

### Community 70 - "Body Map Art"
Cohesion: 0.05
Nodes (38): _BodyCanvas, BodyHeatArt, BodyHeatMap, BodyMap, BodyRecoveryMap, build, focus, fresh (+30 more)

### Community 71 - "Android Themed Widgets"
Cohesion: 0.09
Nodes (7): bindThemedBitmaps(), bindThemedImage(), dayStamp(), DayWidgetProvider, weekdayIndex(), TodayWidgetProvider, WeekWidgetProvider

### Community 72 - "Food Library"
Cohesion: 0.05
Nodes (35): FoodCat, Macros, PortionKind, approx, asset, b, _byId, cat (+27 more)

### Community 73 - "Onboarding"
Cohesion: 0.05
Nodes (36): _bodyRow, _bodyStep, _bottomBar, build, createState, dispose, _finish, gc (+28 more)

### Community 74 - "Rest Alarm"
Cohesion: 0.05
Nodes (32): _android, _androidAlert, _androidPlugin, _applyAudioContext, _buzz, cancel, _clear, _contextFor (+24 more)

### Community 75 - "SVG Icons"
Cohesion: 0.05
Nodes (37): barbell, barbellThin, bars, build, checkBold, chevronLeft, chevronRight, chevronRightBold (+29 more)

### Community 76 - "Catalog & Alias Tests"
Cohesion: 0.06
Nodes (17): main, main, main, calfLifts, main, byName, _hevyNames, main (+9 more)

### Community 77 - "Live Session Model"
Cohesion: 0.05
Nodes (34): clearRest, complete, copy, counts, currentIndex, done, exercises, fromJson (+26 more)

### Community 78 - "App Colors"
Cohesion: 0.06
Nodes (31): accent, accentSoft, amoled, bg, bgRaised, bgRaised2, border, brass (+23 more)

### Community 79 - "SQLite Reader"
Cohesion: 0.06
Nodes (30): _asInt, _be16, _be32, _bytes, _Column, columns, _decode, has (+22 more)

### Community 80 - "Meal Prep Batches"
Cohesion: 0.07
Nodes (30): _b, batch, _BatchCard, _BatchEditor, _BatchEditorState, _BatchLogSheet, _BatchLogSheetState, _byShare (+22 more)

### Community 81 - "Notes State"
Cohesion: 0.06
Nodes (30): backFromNotes, closeNoteEditor, deleteNote, editingNote, editingNoteId, goNotes, importNoteMedia, noteById (+22 more)

### Community 82 - "Session & Export Tests"
Cohesion: 0.06
Nodes (19): main, _session, store, main, session, main, kept, main (+11 more)

### Community 83 - "Import Tests"
Cohesion: 0.07
Nodes (21): bytes, file, main, draw, main, _fitnotesPlain, _fitnotesUnits, _generic (+13 more)

### Community 85 - "Timeline State"
Cohesion: 0.07
Nodes (29): attachShot, backFromCompare, backFromTimeline, bodyTimeline, BodyWindow, compareFromId, comparePose, compareToId (+21 more)

### Community 86 - "Program Templates"
Cohesion: 0.07
Nodes (25): days, id, kProgramTemplates, name, ProgramDay, ProgramTemplate, weekday, bodyweightId (+17 more)

### Community 87 - "Gym Places State"
Cohesion: 0.07
Nodes (28): activePlaceId, addPlace, addPresetPlace, alternativesHere, backFromPlaces, clearPlates, deletePlace, exMineOnly (+20 more)

### Community 88 - "Stats & Profile Tests"
Cohesion: 0.07
Nodes (22): main, defaultPhoto, _host, _liveHost, main, photo, _png, idOf (+14 more)

### Community 89 - "Exercise Model"
Cohesion: 0.07
Nodes (28): aliases, art, copyWith, desc, difficulty, equipment, Exercise, exerciseName (+20 more)

### Community 91 - "Wear & Swap Tests"
Cohesion: 0.07
Nodes (21): bench, main, routineWith, bench, legs, main, other, r (+13 more)

### Community 93 - "Measures State"
Cohesion: 0.07
Nodes (26): addMeasure, backFromMeasures, cmLabel, _cmPerInch, cmStep, deleteMeasure, fromDisplayCm, fromDisplayMeasure (+18 more)

### Community 94 - "Exercise Catalog"
Cohesion: 0.08
Nodes (20): isNoKit, kCalisthenicsEquipment, kCardioExtras, kDifficulties, kEquipment, kExerciseModes, kExercises, kFilterEquipment (+12 more)

### Community 95 - "FIT File Export"
Cohesion: 0.08
Nodes (23): _body, bytes, _categories, crc, _crcTable, data, define, duration (+15 more)

### Community 96 - "Tool Art"
Cohesion: 0.10
Nodes (18): _block, build, dark, _fill, _gloss, height, _hue, id (+10 more)

### Community 97 - "Medal Looks"
Cohesion: 0.10
Nodes (18): base, _bronze, _diamond, _emerald, gem, _gold, icon, ink (+10 more)

### Community 98 - "Localizations Delegate"
Cohesion: 0.10
Nodes (19): AppLocalizations, _AppLocalizationsDelegate, AppLocalizationsAr, AppLocalizationsDe, AppLocalizationsEn, AppLocalizationsEs, AppLocalizationsFa, AppLocalizationsFr (+11 more)

### Community 99 - "Steps State"
Cohesion: 0.11
Nodes (18): askStepsAccess, _freshSteps, _keepDays, loadSteps, refreshSteps, setStepsGoal, setStepsOn, _sk (+10 more)

### Community 100 - "Awards State"
Cohesion: 0.11
Nodes (17): awardCount, awardGoal, awardProgress, awards, awardsSeen, awardValue, awardWonAt, backFromAwards (+9 more)

### Community 101 - "Profile Model"
Cohesion: 0.11
Nodes (17): activity, age, badge, banner, fromJson, handle, heightCm, kDefaultHandle (+9 more)

### Community 102 - "Moments State"
Cohesion: 0.12
Nodes (16): addMoment, backFromMoments, clearMomentPicks, date, deleteMoment, deleteMoments, file, fromJson (+8 more)

### Community 103 - "State Mixins"
Cohesion: 0.24
Nodes (15): AwardsState, LibraryState, MeasuresState, MomentsState, NotesState, NutritionState, PlacesState, RoutinesState (+7 more)

### Community 104 - "Exercise Aliases"
Cohesion: 0.12
Nodes (9): kExerciseAliases, kMergedExercises, kOpenGymIds, kExerciseNameEs, kExerciseStepsEs, kExerciseNameIt, kExerciseStepsIt, kExerciseNameZh (+1 more)

### Community 105 - "App Theme"
Cohesion: 0.13
Nodes (11): amoled, AppTheme, _build, d, dark, disp, f, light (+3 more)

### Community 106 - "Progress Shot Model"
Cohesion: 0.13
Nodes (13): copyWith, date, fromJson, id, isEmpty, kPoses, media, note (+5 more)

### Community 107 - "Settings Water Widget"
Cohesion: 0.14
Nodes (13): flOz, glassStep, _miniBtn, row, showGoalsSheet, showNutritionAbout, showTrackersSheet, showWeekSheet (+5 more)

### Community 108 - "Place Model"
Cohesion: 0.17
Nodes (9): bar, copyWith, equipment, fromJson, GymPlace, id, name, plates (+1 more)

### Community 109 - "Persistence Tests"
Cohesion: 0.18
Nodes (7): expectEverythingIsThere, fillEverything, kFirstId, main, c, main, routineWithThree

### Community 113 - "Glass Dialog Route"
Cohesion: 0.38
Nodes (3): _GlassCount, _GlassDialogRoute, _GlassSheetRoute

### Community 115 - "Level-Up Test"
Cohesion: 0.33
Nodes (5): diamond, main, pushUp, routineWith, workout

## Knowledge Gaps
- **26382 isolated node(s):** `_blurTop`, `_pillSpace`, `_firstAwardWait`, `_nextAwardWait`, `_lastRoute` (+26377 more)
  These have ≤1 connection - possible missing edges. (Counts symbols only; 26640 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **17 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Profile` connect `Profile Model` to `Fit & Nutrition State`?**
  _High betweenness centrality (0.002) - this node is a cross-community bridge._
- **What connects `_blurTop`, `_pillSpace`, `_firstAwardWait` to the rest of the system?**
  _26382 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Localization Hub` be split into smaller, more focused modules?**
  _Cohesion score 0.0014367816091954023 - nodes in this community are weakly interconnected._
- **Why does `GymColors` connect `Home Widgets & Share Cards` to `Profile & Timeline Screens`, `Wear OS Shell`, `Body Map Art`, `Beeper, Radar & Steps`, `Onboarding`, `Nutrition Art`, `App Colors`, `Charts & Painters`, `Exercise & Routine Screens`, `Food Logging Screens`, `Liquid Notch Frame`, `Award Celebrations`?**
  _High betweenness centrality (0.002) - this node is a cross-community bridge._
- **Should `Strings: AR` be split into smaller, more focused modules?**
  _Cohesion score 0.0014641288433382138 - nodes in this community are weakly interconnected._
- **Why does `MainActivity` connect `Android MainActivity` to `Permission Callbacks`?**
  _High betweenness centrality (0.000) - this node is a cross-community bridge._
- **Should `Strings: DE` be split into smaller, more focused modules?**
  _Cohesion score 0.0014641288433382138 - nodes in this community are weakly interconnected._