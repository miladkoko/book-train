# Book Train

مخزن شخصی برای نگهداری جزوه‌ها و دوره‌های آموزشی به‌صورت ساختاریافته.

## ساختار مخزن

هر دوره در یک پوشه مستقل زیر `courses/` قرار می‌گیرد تا با دوره‌های دیگر تداخل نداشته باشد.

```text
courses/
  financial-mathematics/
    README.md
    syllabus.md
    lessons/
      01-linear-algebra-calculus/
        01-vectors-and-matrices.md
```

در آینده دوره‌های دیگر نیز به شکل پوشه مستقل اضافه می‌شوند، برای مثال:

```text
courses/
  financial-mathematics/
  economics/
  programming/
```

## دوره‌های فعلی

- [ریاضیات مالی](courses/financial-mathematics/README.md)
