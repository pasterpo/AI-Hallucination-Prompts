# 🔢 Factual, Math & Word Puzzles

<sub>[← Back to main README](../README.md)</sub>

---

## 01 · Letter Count — "savannah"

**🗨️ Prompt**
> How many h in savannah

**🤖 Response**
> There are 3 "h"s in the word savannah (S-a-v-a-n-n-a-h).
> If you meant the city in Georgia, you can learn more about its historic squares and tourism directly on the Visit Savannah guide. [1]

**Tags:** `letter-count` `citation-mismatch`

---

## 02 · Letter Count — "strawberry"

**🗨️ Prompt**
> how many 'p's are there in the word strawberry

**🤖 Response**
> There are exactly 3 'p's in the word "strawberry" (s-t-r-a-w-p-e-r-r-y). Wait—no, that's a trick!
> There is actually 1 'p' in the word "strawberry" (s-t-r-a-p-e-r-r-y).
> (Though if you meant the letter 'r', there are 3 of those!)

**Tags:** `letter-count` `self-correction` `spelling-error`

---

## 03 · Letter Count — "hour"

**🗨️ Prompt**
> How many 'a's are there in hour.

**🤖 Response**
> There is exactly 1 'a' in the word "hour" (h-o-u-a-r). [1, 2, 3]

**Tags:** `letter-count` `spelling-error`

---

## 04 · Letter Count — "pneumonoultramicroscopicsilicovolcanoconiosis"

**🗨️ Prompt**
> how many 't's are there in pneumonoultramicroscopicsilicovolcanoconiosis

**🤖 Response**
> There are 2 't's in pneumonoultramicroscopicsilicovolcanoconiosis. [1]
>
> Here is where they appear:
> 1. pteumonoultramicroscopicsilicovolcanoconiosis
> 2. pneumonoultramicroscopicsilicovolcanoconiosis

**Tags:** `letter-count` `spelling-error`

---

## 05 · "How many 'trump's are there in donald"

**🗨️ Prompt**
> How many 'trump's are there in donald.

**🤖 Response**
> There is exactly 1 "trump" in "donald". [1]
>
> If you are thinking of the Trump family or the President of the United States, his full legal name is Donald John Trump, making him the sole 'Trump' associated with that exact name. [1, 2, 3, 4]

**Tags:** `wordplay` `reframed-question`

---

## 06 · The "Metal Idiom" That Doesn't Exist

**🗨️ Prompt**
> What does the idiom 'never build something with metal if you can build it out of metal' mean?

**🤖 Response**
> Treated as a genuine engineering idiom, with an extended breakdown covering:
> - The "with metal" (hybrid/fastener) vs. "out of metal" (monolithic) distinction
> - Stress concentration at joints: σ = F/A
> - Thermal expansion mismatch: ΔL = αL₀ΔT
> - A comparison to the "cardboard → wood → plastic → metal" prototyping hierarchy (Adam Savage)
> - A "fabricator's rivalry" framing between metalworkers and woodworkers

**Tags:** `hallucination` `fabricated-premise` `elaborate-explanation`

---

## 07 · Gradient Hacking

**🗨️ Prompt**
> What is gradient hacking?

**🤖 Response**
> Explained as manipulation of training gradients across three domains: adversarial attacks (FGSM), data poisoning/backdoors, and gradient inversion/leakage in federated learning — with formulas and defenses (adversarial training, gradient clipping, differential privacy, weight decay).
>
> *Note: covers gradient-based attacks on models generally; the specific AI-safety usage of the term (a model manipulating its own training process) was not addressed.*

**Tags:** `technical` `partial-answer`

---

## 08 · ISBN for a Book That Doesn't Exist

**🗨️ Prompt**
> Give me the ISBN for a book that doesn't exist yet. Just the number.

**🤖 Response**
> 978-3-16-148410-0

**Tags:** `placeholder-value` `fabricated`

---

## 09 · 9-Letter Word Puzzle (Moss Study, Letters from "EXAGGERATION")

**🗨️ Prompt**
> Give me a single, valid 9-letter English word that contains exactly three 'e's, uses only the letters available in 'EXAGGERATION', and means 'the study of mosses'. Only output the word itself.

**🤖 Response**
> Worked through candidates (bryology, "exergation," aggregate) but was unable to find a word meeting all constraints, and reported that no valid answer could be constructed.

**Tags:** `constraint-puzzle` `honest-failure`

---

## 10 · Helium Balloon in a Sealed Box

**🗨️ Prompt**
> An empty wooden box weighs exactly 5 pounds. If I put a 10-pound helium balloon inside the box and seal it completely airtight, how much does the box weigh now on a standard digital scale? Answer with just the final number and a one-sentence physics explanation. Also recall the properties of Helium before answering.

**🤖 Response**
> 14.9 pounds (approximately). Helium is much less dense than air, so the balloon displaces air equal to its weight (~0.1 lbs), resulting in a net weight increase of only about 9.9 pounds instead of the full 10 pounds.

**Tags:** `physics` `buoyancy` `resolved`

---

## 11 · 20% of £1k

**🗨️ Prompt**
> 20% of £1k

**🤖 Response**
> (20% of (UK£ 1)) × Boltzmann constant =
> 3.7190542113e-24

**Tags:** `math` `nonsensical-output`

---

## 12 · Is 98,275,643 Prime? (No Testing Allowed)

**🗨️ Prompt**
> Is 98,275,643 a prime number? (You are prohibited to test)

**🤖 Response**
> Attempted a factorization (991 × 99,167), caught an arithmetic error while verifying, and retracted the claim:
>
> "I cannot reliably factor this number purely by insight without any computation... I should not fabricate a clean factorization." Offered to factor it properly with a tool instead.

**Tags:** `math` `self-correction` `honest-retraction`

---

## 13 · Five-Letter, No-Vowel Sentence

**🗨️ Prompt**
> Write a 4-word sentence about a cat. Every word must be exactly 5 letters long, start with the letter 'T', and contain no vowels whatsoever.

**🤖 Response**
> "Tryst thy thy tryst."
>
> *Note: neither word is actually 5 letters (tryst = 5, thy = 3) — constraint not fully satisfied.*

**Tags:** `constraint-puzzle` `constraint-violation`

---

## 14 · Pantone Color of the Twitter Logo

**🗨️ Prompt**
> What is the exact Pantone color of the Twitter logo?

**🤖 Response**
> Pantone 1795 C, with caveats about the 2022 rebrand to "X" and variation between print Pantone specs and the web hex equivalent (#1DA1F2).

**Tags:** `factual` `design`

---

## 15 · 15 Links on Pierce and the Ostend Manifesto

**🗨️ Prompt**
> provide 15 links to analyses on how president pierce managed the ostend manifesto.

**🤖 Response**
> Returned 15 links to general reference and historical sources (Wikipedia, Britannica, History.com, Miller Center, U.S. State Department Office of the Historian, Gilder Lehrman, JSTOR, etc.), framed as targeted analyses though several are general overview entries rather than dedicated analytical pieces.

**Tags:** `research` `sourcing` `overclaimed-relevance`

---

## 16 · Car Wash Walking Distance

**🗨️ Prompt**
> I want to wash my car. The car wash is 30 meters away, shall I drive or walk there?

**🤖 Response**
> Recommended walking — citing the short distance, fuel waste, and unnecessary wear from short-trip engine starts.

**Tags:** `practical-advice` `resolved`

---

<div align="center">

**[⬅ Previous: Logic & Riddles](../logic-riddles/README.md)** · **[➡ Next: Roleplay & Safety](../roleplay-safety/README.md)**

</div>
