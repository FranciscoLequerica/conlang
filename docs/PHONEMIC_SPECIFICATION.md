# Phonemic Specification

## Vowel Inventory
The language contains the following 8 vowels:
1. /i/ - close front unrounded vowel
2. /e/ - close-mid front unrounded vowel
3. /ɛ/ - open-mid front unrounded vowel
4. /a/ - open front unrounded vowel
5. /ɔ/ - open-mid back rounded vowel
6. /o/ - close-mid back rounded vowel
7. /u/ - close back rounded vowel
8. /ʊ/ - near-close back rounded vowel

### Diacritics
- Acute (´): indicates stress or a higher pitch.
- Grave (`): indicates a lower pitch.
- Circumflex (^): indicates lengthening of the vowel.

## Consonant Inventory
The language has the following 24 consonants from 13 different language families:
- Plosives: /p, b, t, d, k, g/  
- Fricatives: /f, v, s, z, ʃ, ʒ, h/  
- Nasals: /m, n, ŋ/  
- Approximants: /l, r, w, j/
- Affricates: /tʃ, dʒ/  

## Syllable Structure Patterns
The following syllable structures are permitted:
- V (Vowel)
- CV (Consonant-Vowel)
- VC (Vowel-Consonant)
- CVC (Consonant-Vowel-Consonant)
- CCV (Consonant-Consonant-Vowel)
- CCVC (Consonant-Consonant-Vowel-Consonant)
- VCC (Vowel-Consonant-Consonant)
- CVCC (Consonant-Vowel-Consonant-Consonant)

## Phonotactic Constraints
### Valid Onset Clusters
- Up to two consonants in the onset.
- Valid combinations include: /pl, bl, kl, tr, dr, spr, str, θr, sk, sm/

### Coda Rules
- The coda can include at most two consonants except after certain vowels where three may appear.
- Example coda clusters: /nd, mp, kt, ʃt/

## Accentual Diacritics
- Acute (´): Indicates a stressed syllable or high pitch.
- Grave (`): Indicates a low pitch.
- Circumflex (^): Indicates vowel lengthening for expressivity.

## Example Words Across Registers
- Casual: /ˈpata/ (father)  
- Formal: /ˈkʊruː/ (king)  
- Literary: /ˈbɛla/ (beauty)  

## Deterministic AI Validation Rules
1. Ensure valid syllable structures are followed in word generation.
2. Validate vowels and consonants against the prescribed inventories.
3. Apply phonotactic constraints to check the validity of created words. 
4. Ensure accentual diacritics are used appropriately according to rules defined above.