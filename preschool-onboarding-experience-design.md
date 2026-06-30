# Little Life Books Onboarding Experience Design

## Design Intent

This onboarding should feel like a calm, expert-guided conversation with a parent who is doing something loving for their child. The parent is not "filling out a form." They are helping us understand their child well enough to create a story that feels emotionally true.

The experience should collect 40-60 pieces of information through a sequence of small, meaningful moments. Each screen should ask for one thoughtful decision whenever possible. Progress should feel like a story being assembled, not like a task list being completed.

## Experience Principles

- Ask one meaningful thing at a time.
- Explain why each answer matters in parent-friendly language.
- Use branching to make the experience feel personally responsive.
- Show momentum through collected story fragments, not question counts.
- Make uploading photos feel like preparing a keepsake.
- Avoid clinical or administrative language.
- Prefer "Let's help your child picture..." over "Please provide..."
- Use warm confirmation after emotionally vulnerable answers.
- Keep screens mobile-first, thumb-friendly, accessible, and calm.
- Make the parent feel seen as a careful, loving expert on their child.

## Visual System Direction

- Background: warm off-white with very subtle tint shifts between chapters.
- Typography: generous line height, restrained type scale, editorial but readable.
- Components: soft cards, clear touch targets, low-contrast borders, no visual clutter.
- Color: warm neutrals with terracotta as the primary action color and muted sage only as a secondary success/accent tone.
- Motion: slow, soft, purposeful. Avoid bouncy, gamified, or frantic animation.
- Progress: chapter dots or "Your story is taking shape" moments, not "Question 17 of 52."

## Flow Architecture

The onboarding is organized into six emotional chapters:

1. Meet Your Child
2. What Preschool Feels Like
3. The Goodbye Moment
4. The Day They Will Picture
5. Comforts, People, and Language
6. Make It Look Like Their Life

Each chapter ends with a brief reflection screen that turns collected answers into a tiny story preview.

---

# Screen-by-Screen Experience

## 1. Welcome: "Let's Make Preschool Feel Familiar"

**Screen purpose:** Establish trust, calm the parent, and set the expectation that this will feel gentle.

**Layout wireframe:**
```text
[ Little Life Books ]

Let's make preschool feel familiar.

A few thoughtful details help us create a story
your child can recognize, practice, and return to.

[ Start with my child ]

Already started? [ Continue ]
```

**Primary action:** Start with my child  
**Secondary action:** Continue  
**Microcopy:** "You can skip anything you're unsure about and come back later."  
**Why this screen exists psychologically:** Parents arrive with a mix of hope, anxiety, and limited time. This screen reduces performance pressure and frames the process as care, not homework.  
**Opportunities for delight:** A faint book page texture or soft page-turn shimmer behind the headline.  
**Animation ideas:** Headline fades in first, then the supporting copy, then the button.  
**What happens next:** Begin child identity.

## 2. Child's Name

**Screen purpose:** Create immediate personalization and emotional investment.

**Layout wireframe:**
```text
[ Chapter: Meet Your Child ]

What name should the story use?

This helps your child recognize, "This book is about me."

[ Maya____________ ]

[ Continue ]
```

**Primary action:** Continue  
**Secondary action:** Back  
**Microcopy:** "Use the name your child likes hearing most."  
**Why this screen exists psychologically:** Names create instant ownership and make the parent feel the story is already forming.  
**Opportunities for delight:** As the parent types, show "Maya's story begins..." beneath the field.  
**Animation ideas:** Typed name softly appears on a tiny illustrated book cover.  
**What happens next:** Age and pronouns.

## 3. Age and Story Voice

**Screen purpose:** Determine developmental voice without making the parent think technically.

**Layout wireframe:**
```text
How old is Maya?

Age helps us choose the right rhythm,
words, and amount of detail.

[ 2 ] [ 3 ] [ 4 ] [ 5 ] [ 6 ]

What words should we use for Maya?
[ she/her ] [ he/him ] [ they/them ] [ name only ]

[ Continue ]
```

**Primary action:** Continue  
**Secondary action:** Back  
**Microcopy:** "We use this to make the story sound natural when read aloud."  
**Why this screen exists psychologically:** Combines two low-effort identity questions to create early momentum.  
**Opportunities for delight:** Selected chips gently settle into a "story voice" row.  
**Animation ideas:** Soft chip selection transition with no bounce.  
**What happens next:** Preschool timing.

## 4. When Preschool Begins

**Screen purpose:** Ground the transition in time.

**Layout wireframe:**
```text
When does preschool begin?

A real date can help us build a gentle sense
of "soon" without making it feel too big.

[ Date picker ]
[ I don't know yet ]

[ Continue ]
```

**Primary action:** Continue  
**Secondary action:** I don't know yet  
**Microcopy:** "If the date changes, the story can stay flexible."  
**Why this screen exists psychologically:** Time uncertainty can heighten parent and child anxiety. Naming time creates containment.  
**Opportunities for delight:** If a date is entered, show "We'll help Maya get ready for September."  
**Animation ideas:** A soft calendar page turns once.  
**What happens next:** Prior experience.

## 5. Has This Kind of Day Happened Before?

**Screen purpose:** Understand novelty level.

**Layout wireframe:**
```text
Has Maya been in daycare, preschool,
or a group class before?

This tells us whether preschool should feel
like a brand-new adventure or a familiar next step.

[ First time ]
[ Some classes/daycare ]
[ Previous preschool ]
[ Not sure ]

[ Continue ]
```

**Primary action:** Continue  
**Secondary action:** Back  
**Microcopy:** "There is no better answer. We just meet Maya where she is."  
**Why this screen exists psychologically:** Reassures the parent that the product adapts to the child rather than judging readiness.  
**Opportunities for delight:** Selected card reveals a tiny line: "We'll go slowly." or "We'll build on what she knows."  
**Animation ideas:** Card expands by 4-8px with a gentle shadow.  
**What happens next:** Personality.

## 6. New Situation Style

**Screen purpose:** Capture temperament in parent language.

**Layout wireframe:**
```text
In new places, Maya usually...

This helps us write confidence in a way
that feels true, not forced.

[ Watches first ]
[ Jumps right in ]
[ Stays close, then warms up ]
[ Depends on the day ]

[ Continue ]
```

**Primary action:** Continue  
**Secondary action:** Back  
**Microcopy:** "Slow-to-warm children are not behind. They are gathering safety."  
**Why this screen exists psychologically:** Many parents worry about temperament. This screen normalizes differences.  
**Opportunities for delight:** Gentle expert note appears after selection.  
**Animation ideas:** Selection reveals one sentence of validation.  
**What happens next:** Social style.

## 7. Around Other Children

**Screen purpose:** Shape friendship scenes without pressure.

**Layout wireframe:**
```text
Around other children, Maya is most often...

Friendship in the story should match
how she actually connects.

[ Joins quickly ]
[ Watches first ]
[ Likes one friend ]
[ Plays nearby ]
[ Needs adult help ]

[ Continue ]
```

**Primary action:** Continue  
**Secondary action:** Back  
**Microcopy:** "Parallel play still counts as connection."  
**Why this screen exists psychologically:** Reduces parent anxiety about social performance.  
**Opportunities for delight:** A small preview line: "We'll show friendship gently."  
**Animation ideas:** Cards slide in slowly from below.  
**What happens next:** Interests.

## 8. What Lights Them Up

**Screen purpose:** Collect high-value personalization that brings joy into the book.

**Layout wireframe:**
```text
What does Maya love right now?

Favorite things give the story warmth,
humor, and little details only she would notice.

[ Dinosaurs, bubbles, purple shoes... ]

[ Continue ]
```

**Primary action:** Continue  
**Secondary action:** Skip for now  
**Microcopy:** "Tiny details are welcome."  
**Why this screen exists psychologically:** Moves from anxiety to affection, reminding the parent of the child beyond the transition.  
**Opportunities for delight:** Convert typed interests into small tags below the field.  
**Animation ideas:** Tags appear like collected keepsakes.  
**What happens next:** Chapter reflection.

## 9. Reflection: "We Are Starting to See Maya"

**Screen purpose:** Create momentum and emotional payoff.

**Layout wireframe:**
```text
We are starting to see Maya.

Maya is 3.
She warms up slowly.
She loves dinosaurs and purple shoes.

We'll make her preschool story feel like it belongs to her.

[ Keep going ]
```

**Primary action:** Keep going  
**Secondary action:** Edit details  
**Microcopy:** "A few more details will help us build the preschool day around her."  
**Why this screen exists psychologically:** Parents feel progress through synthesis, not through a progress bar.  
**Opportunities for delight:** A tiny generated "story seed" preview.  
**Animation ideas:** Each collected fact fades in like a page line.  
**What happens next:** Main concerns.

## 10. What Feels Biggest

**Screen purpose:** Identify the emotional center and branch the experience.

**Layout wireframe:**
```text
What feels biggest about preschool right now?

Choose anything that matters.
We'll only ask more about what you select.

[ Saying goodbye ]
[ New teacher ]
[ Making friends ]
[ Bathroom ]
[ Loud classroom ]
[ Not knowing the routine ]
[ Lunch/snack ]
[ Rest time ]
[ Following directions ]
[ Fear of being left ]
[ Maya hasn't seemed worried ]

[ Continue ]
```

**Primary action:** Continue  
**Secondary action:** Back  
**Microcopy:** "You can choose more than one."  
**Why this screen exists psychologically:** Gives the parent control and promises relevance.  
**Opportunities for delight:** Selected concerns become a calm "focus list."  
**Animation ideas:** Unselected cards softly dim after Continue, reinforcing the tailored path.  
**What happens next:** Branch screens based on selections.

## 11A. Branch: Saying Goodbye

**Screen purpose:** Understand separation behavior.

**Layout wireframe:**
```text
When you separate, Maya usually...

This helps us write a goodbye that validates
her feelings and still moves the day forward.

[ Cries or clings ]
[ Gets quiet ]
[ Asks many questions ]
[ Gets upset or angry ]
[ Runs to play ]
[ It varies ]

[ Continue ]
```

**Primary action:** Continue  
**Secondary action:** Skip  
**Microcopy:** "The story can show tears without making them the whole story."  
**Why this screen exists psychologically:** Normalizes hard separation and reduces parent shame.  
**Opportunities for delight:** Expert reassurance appears after selection.  
**Animation ideas:** Calm fade, no celebratory animation.  
**What happens next:** Drop-off routine later receives more detail.

## 11B. Branch: New Teacher

**Screen purpose:** Make the teacher feel like a known helper.

**Layout wireframe:**
```text
Has Maya met the teacher yet?

Knowing this helps us introduce the teacher
as familiar, almost familiar, or brand new.

[ Met in person ]
[ Seen a photo ]
[ Heard the name ]
[ Not yet ]

[ Continue ]
```

**Primary action:** Continue  
**Secondary action:** Skip  
**Microcopy:** "A teacher can become part of the safety story."  
**Why this screen exists psychologically:** Helps transfer attachment safety from parent to school adult.  
**Opportunities for delight:** Teacher card placeholder begins forming.  
**Animation ideas:** Soft reveal of "Ms. Ana can help..." if name is known later.  
**What happens next:** Teacher support question if relevant.

## 11C. Branch: Making Friends

**Screen purpose:** Shape a realistic social success.

**Layout wireframe:**
```text
What part of making friends might feel hardest?

We'll give Maya a small, doable way to join.

[ Feeling shy ]
[ Not knowing what to say ]
[ Worrying others won't play ]
[ Getting too excited ]
[ Not sure ]

[ Continue ]
```

**Primary action:** Continue  
**Secondary action:** Skip  
**Microcopy:** "The story does not need to make her instantly outgoing."  
**Why this screen exists psychologically:** Removes social-performance pressure and replaces it with a tiny script.  
**Opportunities for delight:** Later preview a line of dialogue.  
**Animation ideas:** Selected card becomes a small speech bubble.  
**What happens next:** Optional joining-play phrase.

## 11D. Branch: Bathroom

**Screen purpose:** Make toileting practical and shame-free.

**Layout wireframe:**
```text
What bathroom support might Maya need?

We keep this calm, private, and matter-of-fact.

[ Reminder to go ]
[ Help with clothes ]
[ Help finding bathroom ]
[ Accident reassurance ]
[ Privacy reassurance ]
[ No help needed ]

[ Continue ]
```

**Primary action:** Continue  
**Secondary action:** Skip  
**Microcopy:** "Bathroom routines are just routines."  
**Why this screen exists psychologically:** Reduces parent embarrassment and child shame through neutral framing.  
**Opportunities for delight:** None playful here; delight is restraint and dignity.  
**Animation ideas:** Minimal; simple selection.  
**What happens next:** Bathroom wording later.

## 11E. Branch: Loud or Busy Classroom

**Screen purpose:** Identify sensory supports.

**Layout wireframe:**
```text
What tends to feel like too much?

This lets the story show Maya noticing her body
and getting support before overwhelm builds.

[ Loud voices ]
[ Crowded transitions ]
[ Music/singing ]
[ Bright lights ]
[ Messy play ]
[ Food smells ]

[ Continue ]
```

**Primary action:** Continue  
**Secondary action:** Skip  
**Microcopy:** "Sensitivity is information, not a problem."  
**Why this screen exists psychologically:** Affirms sensory needs and avoids pathologizing.  
**Opportunities for delight:** Show "We'll include a calm option."  
**Animation ideas:** Background subtly quiets after selection.  
**What happens next:** Calming supports.

## 11F. Branch: Routine, Food, Rest, or Directions

**Screen purpose:** Collect practical uncertainty in one adaptable screen.

**Layout wireframe:**
```text
Which part should the story make easier to picture?

Children often relax when they know
what comes first, next, and after.

[ Arrival ]
[ Snack/lunch ]
[ Bathroom ]
[ Rest ]
[ Cleanup ]
[ Pickup ]

[ Continue ]
```

**Primary action:** Continue  
**Secondary action:** Skip  
**Microcopy:** "We can turn unknowns into a simple sequence."  
**Why this screen exists psychologically:** Converts broad anxiety into concrete routine preview.  
**Opportunities for delight:** Selected items line up into a visual day path.  
**Animation ideas:** Small routine tiles arrange left to right.  
**What happens next:** Drop-off chapter.

## 12. Drop-Off Person

**Screen purpose:** Name the adult in the goodbye scene.

**Layout wireframe:**
```text
Who will usually bring Maya to preschool?

The goodbye scene works best when it matches
what will really happen.

[ Mama____________ ]

[ Continue ]
```

**Primary action:** Continue  
**Secondary action:** Back  
**Microcopy:** "Use the word Maya uses."  
**Why this screen exists psychologically:** Makes separation concrete and truthful.  
**Opportunities for delight:** "Mama" appears in a tiny goodbye preview line.  
**Animation ideas:** Text settles into a mini story sentence.  
**What happens next:** Drop-off routine.

## 13. What Drop-Off Will Look Like

**Screen purpose:** Build a predictable sequence.

**Layout wireframe:**
```text
What will drop-off probably look like?

Even a few details help Maya picture
the first minutes of the day.

[ We walk to the classroom door... ]

[ Continue ]
```

**Primary action:** Continue  
**Secondary action:** I'm not sure yet  
**Microcopy:** "Approximate is okay. We can keep the story flexible."  
**Why this screen exists psychologically:** Parents often do not know exact logistics. This lowers precision pressure.  
**Opportunities for delight:** Highlight detected sequence words: walk, cubby, hug, goodbye.  
**Animation ideas:** A faint path line draws as they type.  
**What happens next:** Goodbye words.

## 14. The Goodbye Line

**Screen purpose:** Create a repeatable separation script.

**Layout wireframe:**
```text
What will you say before leaving?

A short, steady phrase can become something
Maya practices before the first day.

[ I love you. I always come back after school. ]

[ Continue ]
```

**Primary action:** Continue  
**Secondary action:** Suggest a gentle phrase  
**Microcopy:** "The best phrase is true, short, and repeatable."  
**Why this screen exists psychologically:** Gives parent and child a shared ritual.  
**Opportunities for delight:** Phrase appears as a keepsake quote on a page edge.  
**Animation ideas:** Quote gently types into a preview page.  
**What happens next:** Safe reassurance.

## 15. What We Can Promise

**Screen purpose:** Prevent false reassurance and protect trust.

**Layout wireframe:**
```text
What is safe and true to include?

Children trust stories more when every promise
matches real life.

[ A grown-up comes back after school ]
[ The teacher can help ]
[ Maya can miss you and still play ]
[ Maya can ask for help ]

[ Continue ]
```

**Primary action:** Continue  
**Secondary action:** Back  
**Microcopy:** "We will not promise anything you do not choose here."  
**Why this screen exists psychologically:** Reframes safety as truth, not perfection.  
**Opportunities for delight:** "Truthful reassurance saved" confirmation.  
**Animation ideas:** Selected promises lock softly into place.  
**What happens next:** Pickup.

## 16. The Return

**Screen purpose:** Anchor the story ending in reunion.

**Layout wireframe:**
```text
Who comes back at pickup?

The story will return to this moment,
because coming back is the heart of preschool safety.

[ Mama____________ ]

What will pickup look like?
[ Mama waits outside the classroom... ]

[ Continue ]
```

**Primary action:** Continue  
**Secondary action:** Back  
**Microcopy:** "The ending matters as much as the goodbye."  
**Why this screen exists psychologically:** Children need a concrete return image, not abstract reassurance.  
**Opportunities for delight:** Show a small "beginning -> return" arc.  
**Animation ideas:** A line connects goodbye to pickup.  
**What happens next:** Chapter reflection.

## 17. Reflection: "The Goodbye Has a Shape Now"

**Screen purpose:** Give emotional relief after separation questions.

**Layout wireframe:**
```text
The goodbye has a shape now.

Mama walks Maya in.
Mama says: "I love you. I always come back."
Mama comes back at pickup.

[ Keep going ]
```

**Primary action:** Keep going  
**Secondary action:** Edit goodbye  
**Microcopy:** "This is the kind of repetition young children can hold onto."  
**Why this screen exists psychologically:** Turns vulnerable information into a coherent safety story.  
**Opportunities for delight:** Mini page preview with the goodbye line.  
**Animation ideas:** Three lines appear in sequence, like a calming breath.  
**What happens next:** Preschool routine.

## 18. School and Classroom

**Screen purpose:** Name the place and adults.

**Layout wireframe:**
```text
What is the school called?
[ Willow Tree Preschool ]

Teacher name, if you know it
[ Ms. Ana ]

Classroom name, if there is one
[ Sunflower Room ]

[ Continue ]
```

**Primary action:** Continue  
**Secondary action:** Skip unknowns  
**Microcopy:** "Names turn new places into places children can talk about."  
**Why this screen exists psychologically:** Familiar labels reduce ambiguity.  
**Opportunities for delight:** Build a tiny school sign preview.  
**Animation ideas:** School name appears on a simple sign illustration.  
**What happens next:** Arrival job.

## 19. The First Job at School

**Screen purpose:** Give the child competence early in the day.

**Layout wireframe:**
```text
What happens first when Maya arrives?

A small job, like hanging a backpack,
can help the day feel less mysterious.

[ Hang backpack, put water bottle away... ]

[ Continue ]
```

**Primary action:** Continue  
**Secondary action:** Not sure yet  
**Microcopy:** "If you know only one step, start there."  
**Why this screen exists psychologically:** Action reduces anxiety; the child has something to do.  
**Opportunities for delight:** "Maya's first school job" label.  
**Animation ideas:** A backpack icon moves onto a hook.  
**What happens next:** Day routine.

## 20. The Day Path

**Screen purpose:** Create a visual mental map of preschool.

**Layout wireframe:**
```text
Which parts of the day should Maya's story show?

We'll turn these into a simple path
from arrival to pickup.

[ Circle time ] [ Play ]
[ Snack/lunch ] [ Bathroom ]
[ Outside ] [ Rest ]
[ Cleanup ] [ Pickup ]

[ Continue ]
```

**Primary action:** Continue  
**Secondary action:** Use a typical preschool day  
**Microcopy:** "Only choose what is likely or true."  
**Why this screen exists psychologically:** Children regulate better when they can anticipate sequence.  
**Opportunities for delight:** Selected pieces become a horizontal "day path."  
**Animation ideas:** Tiles slide into an ordered path.  
**What happens next:** Comfort tools.

## 21. What Helps Maya Feel Calm

**Screen purpose:** Select coping strategies.

**Layout wireframe:**
```text
What helps Maya calm when feelings get big?

We'll use a strategy she can actually practice
inside the story.

[ Hug ]
[ Deep breaths ]
[ Quiet space ]
[ Holding something ]
[ Song or phrase ]
[ Movement ]
[ Needs space ]

[ Continue ]
```

**Primary action:** Continue  
**Secondary action:** Not sure yet  
**Microcopy:** "One familiar tool is better than five new ones."  
**Why this screen exists psychologically:** Focuses on usable regulation, not generic coping advice.  
**Opportunities for delight:** Chosen tool becomes "Maya's calm plan."  
**Animation ideas:** Selected card gently glows once.  
**What happens next:** Comfort object.

## 22. Comfort Object

**Screen purpose:** Include transitional objects truthfully.

**Layout wireframe:**
```text
Does Maya have a comfort object?

If it can be part of school, we can show it.
If not, we can keep it as a home goodbye ritual.

[ Purple dinosaur__________ ]

Can it go to school?
[ All day ] [ Backpack ] [ Rest only ] [ No ] [ Not sure ]

[ Continue ]
```

**Primary action:** Continue  
**Secondary action:** Skip  
**Microcopy:** "We won't place it somewhere it won't really be."  
**Why this screen exists psychologically:** Protects against disappointment while honoring attachment objects.  
**Opportunities for delight:** Object becomes a small illustrated sticker placeholder.  
**Animation ideas:** Object name appears on a tiny label.  
**What happens next:** Family language.

## 23. Words That Sound Like Home

**Screen purpose:** Capture family language.

**Layout wireframe:**
```text
What does Maya call her caregivers?

The right words make reassurance feel familiar.

[ Mama, Daddy____________ ]

Any family phrases we should use?
[ You can do hard things with help. ]

[ Continue ]
```

**Primary action:** Continue  
**Secondary action:** Skip phrase  
**Microcopy:** "Short phrases work beautifully in children's books."  
**Why this screen exists psychologically:** Language carries attachment safety.  
**Opportunities for delight:** Phrase appears as "Possible story refrain."  
**Animation ideas:** Refrain appears between two soft rules.  
**What happens next:** Words to avoid.

## 24. Words to Avoid

**Screen purpose:** Protect emotional safety and family preferences.

**Layout wireframe:**
```text
Are there any words or ideas we should avoid?

Some families avoid phrases like "big kid,"
"don't cry," "brave," or "scary."

[ Do not call her shy... ]

[ Continue ]
```

**Primary action:** Continue  
**Secondary action:** Nothing comes to mind  
**Microcopy:** "This helps the story stay supportive instead of accidentally pressuring."  
**Why this screen exists psychologically:** Gives parents control over tone and avoids harm.  
**Opportunities for delight:** The experience feels premium by being careful here.  
**Animation ideas:** None beyond calm field focus.  
**What happens next:** Trusted people.

## 25. Who Belongs in the Story

**Screen purpose:** Define cast and attachment anchors.

**Layout wireframe:**
```text
Who should appear in Maya's story?

Choose the people or pets who help the story
feel safe and true.

[ Mama ]
[ Daddy ]
[ Sibling ]
[ Grandparent ]
[ Pet ]
[ Teacher ]
[ Other ]

Anyone we should not include?
[ Optional ]

[ Continue ]
```

**Primary action:** Continue  
**Secondary action:** Skip optional  
**Microcopy:** "A smaller cast often makes a stronger story."  
**Why this screen exists psychologically:** Keeps personalization meaningful, not cluttered.  
**Opportunities for delight:** Selected characters populate a quiet "story cast" row.  
**Animation ideas:** Simple initials or photo placeholders fade in.  
**What happens next:** Photos chapter.

## 26. Photo Upload Welcome: "Now Make It Look Like Their Life"

**Screen purpose:** Reframe uploading as keepsake creation.

**Layout wireframe:**
```text
Now make it look like Maya's life.

Photos help the illustrations feel familiar:
her face, her backpack, her classroom,
the people who come back.

[ Add photos ]
[ I'll do this later ]
```

**Primary action:** Add photos  
**Secondary action:** I'll do this later  
**Microcopy:** "You do not need perfect photos. Clear and ordinary is enough."  
**Why this screen exists psychologically:** Upload tasks can feel tedious. This frames them as emotionally meaningful.  
**Opportunities for delight:** Beautiful upload checklist with warm labels.  
**Animation ideas:** A blank book page gains faint photo placeholders.  
**What happens next:** Child photo.

## 27. Child Photo

**Screen purpose:** Collect the only required image.

**Layout wireframe:**
```text
Maya's photo

Required for the illustrated character.

[ Large upload area ]
Face and body reference

Tips:
Clear light. Everyday clothes. No need for perfection.

[ Continue ]
```

**Primary action:** Continue  
**Secondary action:** Choose another photo  
**Microcopy:** "We use this for storybook likeness, not a photo-real portrait."  
**Why this screen exists psychologically:** Removes perfectionism and privacy unease.  
**Opportunities for delight:** After upload: "There she is."  
**Animation ideas:** Photo gently settles into a book-page frame.  
**What happens next:** Caregiver photos.

## 28. People Who Come Back

**Screen purpose:** Collect drop-off and pickup visual references.

**Layout wireframe:**
```text
People in the goodbye and pickup scenes

[ Drop-off caregiver upload ]
[ Pickup caregiver upload ]

These help the first and last pages
feel emotionally connected.

[ Continue ]
```

**Primary action:** Continue  
**Secondary action:** Skip for now  
**Microcopy:** "The reunion page works best when the returning grown-up looks familiar."  
**Why this screen exists psychologically:** Reinforces the therapeutic structure: leaving and returning.  
**Opportunities for delight:** Show "Goodbye" and "Back again" page labels.  
**Animation ideas:** Two photo slots connect with a soft line.  
**What happens next:** Familiar objects.

## 29. Familiar Things

**Screen purpose:** Collect high-recognition objects.

**Layout wireframe:**
```text
Add familiar things Maya may notice.

[ Backpack ]
[ Lunchbox/water bottle ]
[ Comfort object ]
[ Cubby ]
[ Playground ]

[ Continue ]
```

**Primary action:** Continue  
**Secondary action:** Skip for now  
**Microcopy:** "Small objects can make a new place feel known."  
**Why this screen exists psychologically:** Concrete visual cues reduce novelty for children.  
**Opportunities for delight:** Each uploaded object becomes a tiny sticker in a tray.  
**Animation ideas:** Uploaded items slide into a "Maya's world" collection.  
**What happens next:** School photos.

## 30. The School Place

**Screen purpose:** Help the child visually preview the environment.

**Layout wireframe:**
```text
If you have school photos, add them here.

[ School exterior ]
[ Classroom ]
[ Teacher, if allowed ]
[ Cubby area ]
[ Playground ]

[ Continue ]
```

**Primary action:** Continue  
**Secondary action:** Skip for now  
**Microcopy:** "Only upload teacher photos if you have permission."  
**Why this screen exists psychologically:** Previewing real spaces reduces uncertainty.  
**Opportunities for delight:** "Preschool map is getting clearer."  
**Animation ideas:** Slots fill into a gentle collage.  
**What happens next:** Parent goals.

## 31. What You Hope This Helps With

**Screen purpose:** Prioritize outcomes.

**Layout wireframe:**
```text
What would you love this story to help with?

Choose what matters most.

[ Easier drop-off ]
[ Understanding the routine ]
[ Knowing you come back ]
[ Asking for help ]
[ Making friends ]
[ Using a calm tool ]
[ More excitement ]

[ Continue ]
```

**Primary action:** Continue  
**Secondary action:** Back  
**Microcopy:** "This helps us choose the emotional ending."  
**Why this screen exists psychologically:** Invites hope after logistics-heavy screens.  
**Opportunities for delight:** Selected goals become "Maya's story will help her..."  
**Animation ideas:** Goals arrange into a short sentence.  
**What happens next:** Most important goal.

## 32. One Thing Most

**Screen purpose:** Force prioritization gently.

**Layout wireframe:**
```text
If the story helps with one thing most,
what should it be?

[ Knowing Mama comes back after school ]

[ Continue ]
```

**Primary action:** Continue  
**Secondary action:** Use my selections  
**Microcopy:** "A focused story is more powerful than a story trying to solve everything."  
**Why this screen exists psychologically:** Creates a clear product strategy for story generation and reassures the parent about focus.  
**Opportunities for delight:** "We'll make this the heart of the book."  
**Animation ideas:** Text becomes the center line of a story preview.  
**What happens next:** Story style.

## 33. Story Feel

**Screen purpose:** Let the parent choose emotional texture.

**Layout wireframe:**
```text
How should the story feel?

[ Very gentle ]
Soft, slow, reassuring

[ Cheerful ]
Warm and upbeat

[ Practical ]
Clear and routine-focused

[ Playful ]
Light, silly, and bright

[ Continue ]
```

**Primary action:** Continue  
**Secondary action:** Help me choose  
**Microcopy:** "For separation worries, very gentle often works best."  
**Why this screen exists psychologically:** Gives aesthetic control without asking the parent to write creatively.  
**Opportunities for delight:** Tone cards subtly preview sample sentence style.  
**Animation ideas:** Selected tone changes the sample line.  
**What happens next:** Illustration style.

## 34. Illustration Feel

**Screen purpose:** Set visual expectation.

**Layout wireframe:**
```text
What kind of illustrations would Maya love?

[ Soft watercolor ]
[ Warm storybook ]
[ Bright playful ]
[ Simple clean ]
[ Choose for me ]

[ Continue ]
```

**Primary action:** Continue  
**Secondary action:** Choose for me  
**Microcopy:** "We'll keep the images calm and easy to recognize."  
**Why this screen exists psychologically:** Premium products let parents shape taste while keeping expert defaults.  
**Opportunities for delight:** Style cards show subtle sample swatches.  
**Animation ideas:** Swatches gently crossfade.  
**What happens next:** Parent note and format.

## 35. How You'll Use It

**Screen purpose:** Support real-world use.

**Layout wireframe:**
```text
How do you plan to use the story?

[ Read on phone ]
[ Read on tablet ]
[ Print at home ]
[ Professional print ]
[ Share with teacher ]

Would you like a parent note at the end?
[ Yes ] [ No ]

[ Continue ]
```

**Primary action:** Continue  
**Secondary action:** Back  
**Microcopy:** "Repeated reading is where the story does its quiet work."  
**Why this screen exists psychologically:** Connects the product to a practical preparation ritual.  
**Opportunities for delight:** "Bedtime, breakfast, or car line" usage suggestions later.  
**Animation ideas:** Selected formats appear as small device/page icons.  
**What happens next:** Safety review.

## 36. Handle With Care

**Screen purpose:** Capture sensitive boundaries.

**Layout wireframe:**
```text
Is there anything we should handle with care?

Anything sensitive, anything to avoid,
or anything Maya is not ready to hear.

[ Optional text area ]

[ Continue ]
```

**Primary action:** Continue  
**Secondary action:** Nothing to add  
**Microcopy:** "Only share what feels relevant to this preschool story."  
**Why this screen exists psychologically:** Provides emotional safety and respects family complexity.  
**Opportunities for delight:** Delight here is quiet seriousness and trust.  
**Animation ideas:** No decorative motion.  
**What happens next:** Developmental needs.

## 37. Support Needs

**Screen purpose:** Invite accessibility, sensory, language, disability, and neurodivergent needs.

**Layout wireframe:**
```text
Any developmental, language, sensory,
disability, or neurodivergent needs
we should reflect?

This helps us make the story respectful,
accessible, and useful.

[ Optional text area ]

[ Continue ]
```

**Primary action:** Continue  
**Secondary action:** Nothing to add  
**Microcopy:** "We include supports affirmingly, never as something to fix."  
**Why this screen exists psychologically:** Signals inclusion and raises trust with families who often feel misunderstood by generic products.  
**Opportunities for delight:** Affirming helper copy after entry: "Thank you. We'll honor that."  
**Animation ideas:** Minimal.  
**What happens next:** Final story preview.

## 38. Story Preview: "Maya's Preschool Story Is Taking Shape"

**Screen purpose:** Make the parent feel the value before checkout or generation.

**Layout wireframe:**
```text
Maya's preschool story is taking shape.

It will show:
• Mama's goodbye words
• The Sunflower Room
• A quiet plan for loud moments
• The purple dinosaur in her backpack
• Mama coming back at pickup

[ Review my story details ]
[ Create Maya's book ]
```

**Primary action:** Create Maya's book  
**Secondary action:** Review my story details  
**Microcopy:** "You can still edit anything before we create the final story."  
**Why this screen exists psychologically:** Converts effort into visible value and creates emotional closure.  
**Opportunities for delight:** Premium story summary with collected details woven into prose.  
**Animation ideas:** Preview bullets appear as book pages stacking softly.  
**What happens next:** Review/edit or order/generation step.

## 39. Review Details

**Screen purpose:** Let parents edit without re-entering the flow.

**Layout wireframe:**
```text
Review Maya's story details

[ Child ]
[ Preschool day ]
[ Goodbye and pickup ]
[ Comfort tools ]
[ People and photos ]
[ Story style ]

[ Create Maya's book ]
```

**Primary action:** Create Maya's book  
**Secondary action:** Edit any section  
**Microcopy:** "Everything here shapes the story, illustrations, or support plan."  
**Why this screen exists psychologically:** Gives control and prevents anxiety about mistakes.  
**Opportunities for delight:** Each section has a tiny completeness indicator like "Ready" or "Optional details missing."  
**Animation ideas:** Accordion sections open smoothly.  
**What happens next:** Create book.

## 40. Creation Handoff

**Screen purpose:** Transition from input to anticipation.

**Layout wireframe:**
```text
We're ready to create Maya's book.

We'll use your details to build a story that helps her
picture preschool, practice goodbye, and remember
that her grown-ups come back.

[ Create book ]
```

**Primary action:** Create book  
**Secondary action:** Save and finish later  
**Microcopy:** "You did the thoughtful part. Now we turn it into something Maya can hold."  
**Why this screen exists psychologically:** Honors the parent's work and makes the transition feel premium.  
**Opportunities for delight:** Subtle final book-cover preview.  
**Animation ideas:** Page stack closes into a cover with child's name.  
**What happens next:** Payment, generation, or confirmation depending on business model.

---

# Branching Strategy

Branching should be invisible to the parent. The experience should never say "because you selected separation." It should simply continue with a question that feels obviously relevant.

If the parent selects separation or fear of being left:
- Show separation behavior.
- Ask truthful reassurance.
- Emphasize goodbye phrase and pickup return.
- Preview "grown-ups come back" in reflections.

If the parent selects bathroom:
- Ask support needed.
- Ask family wording.
- Ask school routine only if unknown details are not already provided.
- Keep tone neutral and private.

If the parent selects making friends:
- Ask what part is hardest.
- Offer optional joining phrase.
- Include peer connection as small success, not social transformation.

If the parent selects loud classroom:
- Ask sensory triggers.
- Ask regulation supports.
- Include calm space, teacher check-in, or sensory tool.

If the parent selects rest time:
- Ask rest habit.
- Ask comfort supports.
- Avoid promising sleep.

If the parent selects no worries expressed:
- Skip concern branches.
- Ask "Is there anything you are quietly wondering about?"
- Frame story as familiarity-building, not worry-fixing.

---

# Progress Model

Avoid numeric progress. Use chapter labels and emotional milestones:

- "Meet Your Child"
- "What Preschool Feels Like"
- "The Goodbye Moment"
- "The Day They Will Picture"
- "Comforts, People, and Language"
- "Make It Look Like Their Life"
- "Story Preview"

Use reflection screens as progress celebrations:

- "We are starting to see Maya."
- "The goodbye has a shape now."
- "The preschool day is becoming easier to picture."
- "Maya's comfort plan is ready."
- "Her story is taking shape."

---

# Upload Experience

Photo upload should feel like assembling a memory box, not attaching files.

Required:
- Child face/body reference.

Highly recommended:
- Drop-off caregiver.
- Pickup caregiver.
- Backpack.
- Comfort object.
- School exterior.
- Classroom.
- Teacher, if allowed.
- Cubby.
- Playground.
- Lunchbox/water bottle.
- Family photo.
- Pet, if included.

Each upload slot should answer "how this helps":

- Child photo: "Helps Maya recognize herself as the child who can do this."
- Caregiver photo: "Helps the goodbye and return feel real."
- Backpack: "Gives Maya something familiar to find on the page."
- Comfort object: "Lets us show a real calm tool."
- School exterior: "Helps the first arrival feel less unknown."
- Classroom: "Lets the room feel familiar before the first day."
- Teacher: "Helps a new adult feel more recognizable."
- Cubby: "Shows Maya where her things belong."
- Playground: "Adds a positive place to look forward to."
- Lunchbox/water bottle: "Makes snack or lunch feel predictable."
- Family photo: "Helps us include the people who make Maya feel safe."
- Pet: "Adds a familiar home connection if it supports the story."

---

# Accessibility and Calm Interaction Rules

- Minimum 44px touch targets.
- Clear focus states.
- No required color-only meaning.
- Plain-language labels.
- Never place helper text only in tooltips.
- Support save-and-resume from every chapter.
- Allow "I'm not sure yet" wherever parents may not know school logistics.
- Use reduced-motion alternatives.
- Use optimistic autosave language: "Saved" instead of "Your response has been submitted."
- Avoid error language that sounds punitive. Use "Let's add this before continuing."

---

# Signature Product Moments

## The Story Seed
After early identity questions, show a tiny generated sentence:

"Maya is getting ready for the Sunflower Room. She loves dinosaurs, takes her time in new places, and feels safest when she knows what comes next."

## The Goodbye Arc
After drop-off and pickup:

"Mama says goodbye. Maya has help at school. Mama comes back."

## The Calm Plan
After regulation:

"When the room feels loud, Maya can hold her dinosaur, take flower breaths, and ask Ms. Ana for help."

## The Final Preview
Before creation, show the story as a warm outline rather than a form summary:

"This book will help Maya picture her preschool day, practice saying goodbye to Mama, meet Ms. Ana, know where her backpack goes, and remember that Mama comes back at pickup."

These moments are the emotional product. The questionnaire is hidden underneath them.
