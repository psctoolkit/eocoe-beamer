# Beamer theme for the EoCoE project

Welcome to  **EoCoE Beamer Theme** repository! This repository contains a custom Beamer presentation theme designed specifically for the **EoCoE (Energy-oriented Centre of Excellence)** project. It is intended to provide a consistent and professional visual style for all presentations related to EoCoE.

## Features

- **Consistent design**: The theme follows the color scheme and design principles of the other EoCoE documents.
- **Customizable**: While the default design follows the EoCoE style guide, the theme can be customized to suit your specific presentation needs.

## Installation

To use the EoCoE Beamer theme, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/psctoolkit/eocoe-beamer.git
   ```
   Include the theme in your Beamer document by adding the following to the preamble of your LaTeX file:
   ```latex
   \usetheme{eocoe}
   ```
   You can customize the theme further by modifying the provided `beamerthemeeocoe.sty` file or adding your own settings.

### Usage

Once the theme is installed, you can start using it in your Beamer presentations. Here's an example of a basic Beamer presentation with the EoCoE theme:

```latex
\documentclass{beamer}
\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage{minted}

\usetheme{eocoe}

\title{The EoCoE Project}
\subtitle{Say hello!}
\date[F2F]{F2F Meeting - BSC, Barcellona, November 27, 2024}
\author[Fabio]{Fabio Durastante}
\institute{Università di Pisa}
\email{fabio.durastante@unipi.it}
\web{fdurastante.github.io}

\begin{document}
	
	\begin{frame}[plain]
		\titlepage
	\end{frame}
	
	\section{Titlepage}
	
	\begin{frame}[fragile]{The EoCoE Beamer theme}{Say hello!}
	
	Hello, world!
	
	\end{frame}

\backmatter
\end{document}
```

## Contributing

We welcome contributions to improve the EoCoE Beamer theme! If you have suggestions or bug fixes, feel free to open an issue or submit a pull request.

## License

This project is licensed under the GPL3 License - see the LICENSE file for details.

## Contact

For questions or feedback, please contact us through GitHub issues.
