# وثيقة ملف: ops.md
## 1. الوظيفة الأساسية للملف
 patched operations for PyTorch. يوفر سياقاً لتبديل العمليات الأساسية في PyTorch مؤقتاً.

## 2. الدوال والكلاسات (Functions & Classes)
- **use_patched_ops()**: سياق (context manager) يبدل عمليات PyTorch (Linear, Conv2d, Conv3d, GroupNorm, LayerNorm) بعمليات معدّلة مؤقتاً.

## 3. الاعتماديات والعلاقات
- الملفات التي تستدعي هذا الملف: modules/patch_clip.py
- الملفات التي يستدعيها هذا الملف لتشغيله: torch.nn