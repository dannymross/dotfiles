if (interactive() || isatty(stdout())) {
    options(colorout.verbose = 0)
    suppressMessages(suppressWarnings({
        if (require("colorout", quietly = TRUE)) {
            # Gruvbox color scheme by @sjlva
            colorout::setOutputColors(
                index    = "\x1b[38;2;215;153;33m",
                normal   = "\x1b[38;2;235;219;178m",
                negnum   = "\x1b[38;2;211;134;155m",
                number   = "\x1b[38;2;236;239;244m",
                zero     = "\x1b[38;2;211;211;211m",
                infinite = "\x1b[38;2;250;189;47m",
                string   = "\x1b[38;2;184;187;38m",
                date     = "\x1b[38;2;254;128;25m",
                const    = "\x1b[38;2;250;189;47m",
                true     = "\x1b[38;2;236;239;244m",
                false    = "\x1b[38;2;211;134;155m",
                warn     = "\x1b[38;2;250;189;47m",
                stderror = "\x1b[38;2;204;36;29m",
                error    = "\x1b[38;2;204;36;29m",
                verbose  = FALSE
            )
        }
    }))
}
