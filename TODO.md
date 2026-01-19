# TODO: Add Tab Feature to Lumina IDE

## Steps to Complete
- [ ] Modify __init__ to initialize notebook and tabs dictionary
- [ ] Update create_editor_area to create ttk.Notebook and default tab
- [ ] Update open_file method to create new tabs for opened files
- [ ] Modify highlight_syntax to highlight_syntax_for(text_widget) for specific text widgets
- [ ] Update on_key_release to work with specific text widgets
- [ ] Update run_lexer to use the current active tab's text widget
- [ ] Add on_tab_changed method to update header label on tab switch
- [ ] Add setup_highlight_tags_for(text_widget) to set up tags per text widget
