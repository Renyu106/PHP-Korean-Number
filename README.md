
# 한글 숫자 변환기 (Korean Number Converter)

🔢 숫자를 한글로 변환하는 PHP 라이브러리입니다.

## 소개 💡

이 라이브러리는 숫자를 한글 표현으로 변환해주는 기능을 제공합니다
"경"(10^16)까지의 큰 숫자를 지원하며, 음수와 0도 자연스럽게 처리합니다

## 사용 방법 🚀

```php
$Converter = new KoreanNumberConverter();

echo $Converter->Convert(1234);        // 출력: 천이백삼십사
echo $Converter->Convert(0);           // 출력: 영
echo $Converter->Convert(-5000);       // 출력: 마이너스오천
echo $Converter->Convert(1000000);     // 출력: 백만
```

## 주요 기능 ✨

- 0부터 경(10^16)까지의 숫자 변환 지원
- 음수 지원
- 단위별 조사 처리 (십, 백, 천, 만, 억, 조, 경)
- 엄격한 타입 체크 (strict_types)
- 의존성 없는 독립 실행
- PSR-4 규격 준수


