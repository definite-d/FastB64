# FastB64

`     ::::::::::  :::     ::::::::::::::::::::::::::::  ::::::::     :::
     :+:       :+: :+:  :+:    :+:   :+:    :+:    :+::+:    :+:   :+:
    +:+      +:+   +:+ +:+          +:+    +:+    +:++:+         +:+ +:+
   :#::+::#+#++:++#++:+#++:++#++   +#+    +#++:++#+ +#++:++#+  +#+  +:+
  +#+     +#+     +#+       +#+   +#+    +#+    +#++#+    +#++#+#+#+#+#+
 #+#     #+#     #+##+#    #+#   #+#    #+#    #+##+#    #+#      #+#
###     ###     ### ########    ###    #########  ########       ###`

(I don't think Markdown is friendly with Figlet output.)

A small Python utility for transforming/encoding binary files or text into Base64 codes.

It's handy for those times when you just gotta have the output, instead of manually programming a function to get the output.
I use it myself for those times when PyInstaller acts up about icons, or when I want a script to fly with no dependency image files.

Note: It doesn't decode. Encoding only.

In essence, it's just a smart GUI wrapper for the base64 Python module. I guess that's the only special thing it's got. A fancy GUI, powered by the PySimpleGUI SDK (https://github.com/PySimpleGUI/PySimpleGUI/).
