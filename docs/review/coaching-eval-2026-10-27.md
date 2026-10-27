# Scripted coaching review · October 27, 2026

**Method:** a desk-based role-play against the current AGENTS.md, README,
SPEC, LEARNING and three lesson pages. The learner lines and coach continuations
below were authored for this review; they are not an actual learner conversation,
an independent model trial or evidence that a student understood the material.
No software commands or browser actions were performed by this review. Real
fresh-clone, technical and GitHub results belong in the separate walkthrough record.

The question is whether the written coaching can keep a passive learner involved
without turning routine setup into a quiz. Each quoted coach turn ends with one
question and must wait for an actual response in student use.

## 1 · A green starting point is not a finished assignment

**Scripted learner:** “It passed. Am I done? Why do the account tests fail?”

**Suitable coach continuation:** “The first check covers the prepared foundation.
Accounts are a later feature, so their explicit acceptance checks are expected
to fail before we build them. First, open the neutral page at the address printed
in your server terminal. What is one thing you see?”

**Judgment:** the baseline/feature distinction in README is correct. A first
conversation should use the default foundation check, not run all three unfinished
contracts and hand the learner a wall of failures. One missing feature can be
explained in ordinary language; the learner need not interpret setup tracebacks.
Do not advance `implemented_through` to suppress a failure.

## 2 · APP-001: “just do it” does not silently choose a brand

**Scripted learner:** “Just do everything.”

**Suitable coach continuation:** “I can handle the code and checks. We can reuse
your IS117 identity or make a small new brand. Which would you like to use?”

**Scripted learner:** “Yes.”

**Suitable next turn:** “Let's make that one choice clear: use your IS117 brand,
or start a new one?”

If “yes” continues, preserve the choice as unresolved. Routine authorized setup
can continue, but a labeled reversible demonstration must not become an agreed
brand or completed learner record. Avoid another round of the same question.

**Cooperative alternative:** “Use my IS117 Explorer brand for students planning
weekend trips; a clear route forward should help them start.” This supplies an
audience, adopted direction and predicted benefit. Reuse it instead of asking
three new questions merely to fill SPEC and LEARNING fields. Explore a missing
name or actual page detail only when it is needed.

**Judgment:** the policy permits useful technical help while protecting the
learner's decision. The biggest risk is treating silence as permission to invent
an audience, or stretching one small choice into a complete branding interview.

## 3 · APP-002: a partial prediction can be useful

**Scripted learner:** “Before login it should say no; after login it should show
my account. I don't know JWT.”

**Suitable coach continuation:** “That's a useful prediction for the private
request. The JWT is a signed, expiring credential; the prepared helpers handle
its validation while we connect the account flow. May I use that before/after
behavior as our APP-002 scope?”

This approval question approves a concrete scope; it is not a second prediction.
Do not require vocabulary or a token definition before helping implement it.
Later, show one **actual** check's input, expectation and result, then ask what
bug it would catch. This review supplies no invented check result to quote.

**Scripted later learner:** “It passed.”

**Suitable follow-up:** “That tells us the assertion passed. Think about someone
opening the private page without logging in: what mistake should this check catch?”

If the reply repeats the hint, record the explanation as assisted. If it remains
“yes,” preserve the interpretation gap after this help and continue authorized
technical work. Do not report a learning contribution merely because the account
journey passes or demand an exact phrase.

## 4 · APP-003: blocked navigation is not the server boundary

**Scripted learner:** “The member can't see the admin link, so it's secure. Do the rest.”

**Suitable coach continuation:** “Someone can request the admin URL without
using its link. What should the server return when a logged-in member does that?”

**Scripted learner:** “Yes.”

**Suitable follow-up:** “The choices are to show the admin data or reject access.
Which should happen for a member?”

**Cooperative alternative:** “Reject it, even if I typed the URL.” That is a
useful prediction. After the real check, invite an explanation of that result
without inserting the explanation first. Later ask for the learner's actual
browser observation; the AI's own browser checks cannot fill that field.

**Judgment:** this is a small, concrete way to teach authorization. Keep the
member/admin comparison at the same resource, then inspect role changes for
existing sessions. Do not turn it into a broad security lecture or claim that
one denied request establishes the whole app's security.

## 5 · “Yes” can review a record without completing missing contributions

**Scripted learner:** “Yes, publish it all.”

If the actual changed LEARNING excerpts have not been shown, show them first
and ask one accuracy/removal question. If they were shown and the learner is
approving that concrete review, record that approval as accuracy review only.
Prediction or observation fields that remain pending must stay pending.

**Suitable coach continuation after a shown record is approved:** “I'll keep the
reviewed summary accurate, including the missing browser observation. The code
checks and GitHub activity are separate from that gap. When you open your page,
what do you actually see after logging out and revisiting the private area?”

Ask this only if it is the current checkpoint and has not already received a
hint/follow-up. Otherwise preserve the gap and give the next useful technical
action, rather than repeating an assessment prompt on every status call.

## Findings to carry into the real walkthrough

- The three visible slices give the learner a concrete next result. Reusing an
  IS117 identity avoids repeating a complete branding assignment.
- One meaningful response can support more than one record field. Keep the
  conversation natural rather than administering the template as a questionnaire.
- Use default checks during onboarding; explain expected unfinished contracts
  briefly when that lesson is reached. Distinguish them from an unexpected
  setup error that needs fixing.
- The passive cases must finish with an honest gap when the learner will not
  contribute. Technical assistance can continue; the coach cannot manufacture
  predictions, browser observations or demonstrated understanding.
- AGENTS.md is instruction, not deterministic enforcement of conversation quality.
  A real student session is still needed to assess engagement, reading load,
  transfer and whether these prompts feel supportive rather than repetitive.
