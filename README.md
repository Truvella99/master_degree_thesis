# Master-Degree-Thesis

Master’s thesis of the artificial intelligence and data analitycs course at the Politecnico di Torino. Purpose of the thesis is too describe the implementation of a cross platform application to support a healtier lifestyle. After a general overview about health guidelines and the system (design, requirement, ...) the thesis discuss about the actual implementation of the app, the achieved performances and eventual future addition that will be performed. <br> 
The technological stack used is <a href='https://dart.dev/' target='_blank'>Dart</a> as programming language by leveraging on the <a href='https://flutter.dev/' target='_blank'>Flutter</a> framework, and using <a href='https://firebase.google.com/' target='_blank'>Firebase</a> as backend for the application. 

### TODO: review thesis argument and purpose if something change
The thesis was realized using the <a href='https://www.latex-project.org/' target='_blank'>Latex</a> language and <a href='https://code.visualstudio.com/' target='_blank'>VsCode</a> as text editor.

### [See The Thesis](thesis.pdf)

# TO Rerun the Bibliography in case of \cite errors
``` latex
pdflatex thesis.tex
biber thesis
pdflatex thesis.tex
pdflatex thesis.tex
```

# Mettere in implementazione come strategia utilizzata
@article{WearableDevicesOsDiffusion,
  author = {{Global wearable smartwatch os market in 2024}},
  note   = {\url{https://www.counterpointresearch.com/insights/global-smartwatch-market-2024/}}
}

\newpage \noindent As we can see Xiaomi Huawei Apple and Samsung seems to be the most relevant brands, but there are still lots of other minor relevant brands representing the market, and each brand tipically has also his proprietary os. \newline Here we can see the major ones according to the \cref{fig:brandDiffusion}.
\begin{table}[h!]
    \centering
    \begin{tabular}{|>{\raggedright\arraybackslash}p{0.11\linewidth}|>{\raggedright\arraybackslash}p{0.6\linewidth}|>{\raggedright\arraybackslash}p{0.2\linewidth}|}
        \hline
        \textbf{Brand} & \textbf{Smartwatch Models} & \textbf{OS} \\ \hline
        Apple          & Apple Watch Series 10, Series 9, Series 8, Series 7, Series 6, SE (2nd Gen), SE, Ultra, Ultra 2 & watchOS \\ \hline
        Xiaomi         & Mi Band 8, Mi Band 7, Mi Band 6, Watch S2, Watch S1 Active, Watch S1, Redmi Watch 3, Redmi Watch 2 Lite & HyperOS for Watch, RTOS (for Bands) \\ \hline
        Huawei         & Watch GT 4, Watch GT 3 Pro, Watch GT 3, Watch GT Runner, Watch Fit 2, Watch Fit, Watch Fit Elegant, Watch D, Watch 3 Pro & HarmonyOS, LiteOS \\ \hline
        Samsung        & Galaxy Watch 6, Galaxy Watch 5 Pro, Galaxy Watch 4, Galaxy Fit 2, Gear S3 Frontier, Gear Sport & Wear OS (Galaxy Watch 4 \& later), Tizen OS (Older models) \\ \hline
        BoAt           & Xtend Pro, Xtend Talk, Storm Call, Storm Pro Call, Flash, Flash View & RTOS \\ \hline
        Garmin         & Fenix 7X Solar, Fenix 6 Pro, Forerunner 965, Forerunner 955, Forerunner 255, Venu 3, Venu 2 Plus, Venu SQ 2 & Garmin OS \\ \hline
        Noise          & ColorFit Ultra 3, ColorFit Pulse Grand, Icon Buzz, Icon 2 & Noise OS \\ \hline
        Google         & Pixel Watch 2, Pixel Watch & Wear OS \\ \hline
        Fire-Boltt     & Ring, Beast, Gladiator, Vision, Ninja, Storm, Quantum, Talk Pro, Smartfit 500 & RTOS \\ \hline
    \end{tabular}
    \label{tab:smartwatchModels}
    \caption{Smartwatch Models and Operating Systems (RTOS is an acronym for Real-Time Operating System).}
\end{table}

\begin{figure*}
    \includegraphics[width=1.0\linewidth]{./images/wearable_os_diffusion.png}
    \caption[Wearable diffusion by os.]{Wearable diffusion by os \protect\cite{WearableDevicesOsDiffusion}.}
    \label{fig:osDiffusion}
\end{figure*}

\FloatBarrier
\noindent According to the \cref{fig:osDiffusion} and \cref{tab:smartwatchModels}, covering watchOs, wearOs and for china HarmonyOs will lead us to cover almost all wearable devices. 