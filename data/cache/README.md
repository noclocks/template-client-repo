# Cache

> [!NOTE]
> Store `cache` data here, or *interim* data that is generated during the data processing pipeline and cached to speed up
> processing. Typically anything in this folder will be `.gitignore`'d.
>
> For `R` projects, we use the `qs` (quick serialization) package to cache data. This is a good practice to speed up
> processing and avoid re-running expensive data processing steps.
