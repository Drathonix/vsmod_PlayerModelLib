# 1.26.0-pre.1 - Changelog
* Made the mod bare-minimum compatible with 1.23-pre.1, it actually compiles and runs without crashes.
* 1.23's custom armor will render but it is unlikely to work properly on non-humanoid models for obvious reasons.
* Fixed a bug with VariantTraits where part variants with the same name in different skin parts would inherit traits from both parts.
* Added the minimum required game version and my name to authors list in modinfo.json.
* Added logging suppression patch for when a shape is missing a keyframe element, usually this is intentional and can be caused when a model part is hidden by hats as in the case of the Bixo mod.