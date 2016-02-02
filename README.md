# Periodic-Table-JSON
A json of the entire periodic table. Feel free to use it in your projects.

<p>
Temperatures such as boiling points and melting points are given in degrees kelvin.
Densities are given in g/L and molar heat in (mol*K)
Information that is missing is repersented as null. Some elements may have an image link to their spectral bands.
All elements have a three sentence summary from wikipedia. Currently the color tag is useless, so please use appearance instead.</p>
<code>
Here's an example of how it's formatted:
{
  Hydrogen": {
		"symbol": "H",
		"number": "1",
		"period": 1,
		"category": "diatomic nonmetal ",
		"atomic_mass": 1.008,
		"color": "colorless",
		"appearance": "colorless gas",
		"phase": "Gas",
		"melt": 13.99,
		"boil": 20.271,
		"density": 0.08988,
		"discovered_by": "Henry Cavendish",
		"molar_heat": 28.836,
		"named_by": "Antoine Lavoisier",
		"spectral_img": "https://en.wikipedia.org/wiki/File:Hydrogen_Spectra.jpg",
		"summary": "Hydrogen is a chemical element with chemical symbol H and atomic number 1. With an atomic weight of 7000100794000000000♠1.00794 u, hydrogen is the lightest element on the periodic table. Its monatomic form (H) is the most abundant chemical substance in the Universe, constituting roughly 75% of all baryonic mass.",
		"ypos": 1,
		"xpos": 1
	}
}
</code>