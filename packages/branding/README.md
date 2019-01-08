# Theia Branding Extension

See [here](https://www.theia-ide.org/doc/index.html) for a detailed documentation.

Allows applications to set their custom branding options, namely a menu, and main icon by
specifying the following `BrandingProps` and using the `BrandingService`.

```ts
brandingTheme: BrandingTheme = {
    /**
     * The main icon for the application.
     */
    mainIcon: (theme: Theme) => string,

    /**
     * The menu icon for the application.
     */
    menuIcon: (theme: Theme) => string,

    /**
     * The main icon size.
     */
    mainSize: string;
}
```

If no custom branding properties are provided, the **default** fallback is **Theia** branding.

## License
- [Eclipse Public License 2.0](http://www.eclipse.org/legal/epl-2.0/)
- [一 (Secondary) GNU General Public License, version 2 with the GNU Classpath Exception](https://projects.eclipse.org/license/secondary-gpl-2.0-cp)
