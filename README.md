# React Parallax Card Grid

🎨 **21stdev** uyumlu React component - Parallax efektli kart grid sistemi

## 🚀 Özellikler

- ✨ **Hover Scale Efekti** - Mouse ile üzerine gelince kartlar büyür
- 🌊 **Parallax Scroll** - Scroll ederken kartlar paralaks hareket eder
- 📱 **Responsive** - Her ekran boyutunda çalışır
- ♿ **Accessible** - Reduced motion desteği
- 🎯 **TypeScript** - Tam type güvenliği
- 🎨 **Tailwind CSS** - Modern styling

## 🛠️ Kullanım

### 21stdev'de Kullanım

Bu component [21stdev](https://21st.dev) formatında hazırlanmıştır. Doğrudan kopyalayıp kullanabilirsiniz.

**Dosyalar:**
- `component.tsx` - Ana component
- `default.tsx` - Demo ve örnek kullanım
- `index.css` - Tailwind CSS konfigürasyonu

### Props

```tsx
interface ParallaxCardGridProps {
  items?: ReactNode[];        // Grid içeriği (opsiyonel)
  gap?: number;              // Kartlar arası boşluk (varsayılan: 16)
  columns?: number;          // Sütun sayısı (varsayılan: 3)  
  intensity?: number;        // Parallax yoğunluğu (varsayılan: 1)
  className?: string;        // Ek CSS sınıfları
}
```

### Örnek Kullanım

```tsx
import { Component } from "./component";

const customItems = [
  <div className="space-y-3">
    <h3 className="text-lg font-semibold">Başlık</h3>
    <p className="text-sm text-muted-foreground">Açıklama</p>
  </div>
];

export default function MyDemo() {
  return (
    <Component
      items={customItems}
      gap={24}
      columns={3}
      intensity={2}
    />
  );
}
```

## 🎯 Demo

Component'i 21stdev'de görmek için [buraya tıklayın](https://21st.dev).

## 📄 License

MIT License - detaylar için [LICENSE](LICENSE) dosyasına bakın.

## 👨‍💻 Geliştirici

[Özhan Gebeşoğlu](https://github.com/ozhangebesoglu)
