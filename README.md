# GTU Physics Ruby vs He-Ne laser compare, plus E = hc/lambda numericals (exam 1240 eV.nm)

GTU Hero's Physics guide, from 22 official papers, found a Ruby laser construction-and-working question in all 9 Group I (3110011) papers, usually for 7 marks, and He-Ne in 6 of 9. On the new scheme (BE01000021 / BE01R00021), all 4 papers so far have a laser question, often with population inversion or a metastable state. Yeh page un dono lasers ka compare table hai, plus a photon-energy numerical: E = hc/lambda. The default wavelengths are the textbook ones (Ruby 694.3 nm, He-Ne 632.8 nm). Practice pulse-energy values are my own, not from a GTU paper.

Live page: https://princeadvant.github.io/gtu-physics-laser-ruby-hene-compare/

## Facts used

- Ruby: solid-state, 3-level, Cr3+ in Al2O3, optical pumping by a xenon flash lamp, pulsed output at 694.3 nm (red), ends of the rod silvered.
- He-Ne: gas, 4-level, helium-neon mixture, electrical discharge, continuous (CW) output at 632.8 nm (red, most common line), mirrors outside the tube.
- A 3-level laser is harder to invert than a 4-level one, because the lower level of the laser transition is the ground state.
- Exam numericals usually take hc = 1240 eV.nm (or 12400 eV.Angstrom). Energy in eV = 1240 / lambda(nm). Frequency f = c / lambda, with c = 3 x 10^8 m/s unless the question gives another value.
- Population inversion: a higher energy state has more atoms than a lower one. A metastable state lives long enough for that to happen, which is why it is needed for lasing.

## Test

`node test.js` checks the calculations against hand-worked values and prints `All checks passed`.

## Tips

- For a 7-mark compare, write 6 to 8 rows (medium, levels, pumping, output, wavelength, resonator, and why 4-level is easier to invert), plus one labelled energy-level sketch for each.
- Say which constant you used for hc. 1240 eV.nm and 12400 eV.Angstrom are the same. Do not mix nm with Angstrom.
- Laser applications (8 of 9 Group I papers) is a separate short note: surgery, welding and cutting, CD/barcode reading, holography, optical fibre communication, and so on. Keep 6 points ready.
- Group 2 (3110018) does not have a Lasers unit. It does ask Einstein coefficients and matter-radiation interaction under Light-semiconductor. Check your subject code on the hall ticket.

Old Physics papers by code (3110011, 3110018, BE01000021) and the questions that actually repeat: [GTU Hero](https://gtuhero.com/blogs/gtu-physics-paper-sem-1-2-pyq) (GTU Hero is my project).
