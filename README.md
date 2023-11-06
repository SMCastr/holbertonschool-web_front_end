README.md : notes.md
    @echo "  GEN   $@"
    @pandoc -f markdown -t gfm -o $@ $<