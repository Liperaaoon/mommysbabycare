import React, { useState, useEffect, useRef } from 'react';
import { 
  Heart, 
  Star, 
  MapPin, 
  Clock, 
  CheckCircle, 
  Instagram, 
  MessageCircle, 
  Menu,
  X,
  ShieldCheck,
  ChevronDown,
  ChevronUp,
  Sparkles,
  Baby,
  Smile,
  ArrowRight,
  Award,
  Users,
  Image as ImageIcon
} from 'lucide-react';

/* CONCEITO: "Baby Pastel & Legibilidade Mobile First"
  Cores: 
  - Rosa Bebê (Destaques): #FFB7C5
  - Azul Bebê (Destaques): #BAE1FF
  - Fundo: #FFFDF7
  - TEXTO: text-gray-900 (Títulos) e text-gray-700 (Corpo)
*/

// Componente para animar os números
const AnimatedNumber = ({ end, duration = 2000, suffix = "" }) => {
  const [count, setCount] = useState(0);
  const countRef = useRef(null);
  const [isVisible, setIsVisible] = useState(false);

  useEffect(() => {
    const observer = new IntersectionObserver(
      ([entry]) => {
        if (entry.isIntersecting) {
          setIsVisible(true);
        }
      },
      { threshold: 0.5 }
    );

    if (countRef.current) {
      observer.observe(countRef.current);
    }

    return () => observer.disconnect();
  }, []);

  useEffect(() => {
    if (!isVisible) return;

    let startTime;
    let animationFrame;

    const step = (timestamp) => {
      if (!startTime) startTime = timestamp;
      const progress = Math.min((timestamp - startTime) / duration, 1);
      const easeOutQuart = 1 - Math.pow(1 - progress, 4);
      setCount(Math.floor(easeOutQuart * end));

      if (progress < 1) {
        animationFrame = requestAnimationFrame(step);
      }
    };

    animationFrame = requestAnimationFrame(step);
    return () => cancelAnimationFrame(animationFrame);
  }, [end, duration, isVisible]);

  return <span ref={countRef}>{count}{suffix}</span>;
};

const App = () => {
  const [isMenuOpen, setIsMenuOpen] = useState(false);
  const [scrolled, setScrolled] = useState(false);
  const [openFaq, setOpenFaq] = useState(null);
  
  const scrollRef = useRef(null);
  const infoScrollRef = useRef(null);
  const [isPaused, setIsPaused] = useState(false);
  const [isInfoPaused, setIsInfoPaused] = useState(false);

  useEffect(() => {
    const handleScroll = () => setScrolled(window.scrollY > 20);
    window.addEventListener('scroll', handleScroll);
    return () => window.removeEventListener('scroll', handleScroll);
  }, []);

  // Auto-scroll Hall da Fofura
  useEffect(() => {
    const scrollContainer = scrollRef.current;
    if (!scrollContainer) return;
    const scrollSpeed = 1; 
    const scrollIntervalTime = 30; 
    const scrollInterval = setInterval(() => {
      if (!isPaused && scrollContainer) {
        if (scrollContainer.scrollLeft + scrollContainer.clientWidth >= scrollContainer.scrollWidth - 1) {
          scrollContainer.scrollTo({ left: 0, behavior: 'auto' });
        } else {
          scrollContainer.scrollLeft += scrollSpeed;
        }
      }
    }, scrollIntervalTime);
    return () => clearInterval(scrollInterval);
  }, [isPaused]);

  // Auto-scroll Portfólio
  useEffect(() => {
    const scrollContainer = infoScrollRef.current;
    if (!scrollContainer) return;
    const scrollSpeed = 1; 
    const scrollIntervalTime = 40; 
    const scrollInterval = setInterval(() => {
      if (!isInfoPaused && scrollContainer) {
        if (scrollContainer.scrollLeft + scrollContainer.clientWidth >= scrollContainer.scrollWidth - 1) {
          scrollContainer.scrollTo({ left: 0, behavior: 'auto' });
        } else {
          scrollContainer.scrollLeft += scrollSpeed;
        }
      }
    }, scrollIntervalTime);
    return () => clearInterval(scrollInterval);
  }, [isInfoPaused]);

  const toggleFaq = (index) => setOpenFaq(openFaq === index ? null : index);

  const testimonials = [
    { name: "Geórgia Martins", text: "Pontualidade e cuidado excepcionais. A Raquel explicou tudo e respeitou o tempo da minha bebê." },
    { name: "Jessika Rezende", text: "Minhas meninas não choraram! A técnica do ponto neutro realmente funciona. Profissionalismo puro." },
    { name: "Adriana Shintani", text: "Ambiente impecável e limpo. Muito mais que humanizado, foi perfeito. Super recomendo." }
  ];

  const faqs = [
    { q: "Qual a idade ideal para furar?", a: "Para garantir a segurança imunológica do seu bebê, recomendamos realizar o procedimento após as primeiras vacinas (a partir de 2 meses)." },
    { q: "O procedimento dói?", a: "Usamos um protocolo 'Dor Zero' com anestésico tópico potente e localização do ponto neutro da orelhinha (acupuntura)." },
    { q: "Quais materiais são usados?", a: "Apenas materiais nobres e estéreis: Aço Cirúrgico 316L, Titânio Grau Implante ou Ouro 24k." },
    { q: "Como funciona o Home Care?", a: "Levamos todo o consultório até sua casa em Mogi ou Santos. Segurança total sem sair do conforto do lar." }
  ];

  const galleryImages = [
    "https://i.postimg.cc/Pr4Yp0Qs/Captura-de-tela-2026-01-16-121813.png",
    "https://i.postimg.cc/5tZCWJb9/Captura-de-tela-2026-01-16-121806.png",
    "https://i.postimg.cc/j2hwfJNH/Captura-de-tela-2026-01-16-121727.png",
    "https://i.postimg.cc/Bnz823LW/Captura-de-tela-2026-01-16-121720.png",
    "https://i.postimg.cc/d1PLS9jd/Captura-de-tela-2026-01-16-121711.png"
  ];

  const portfolioImages = [
    "https://i.postimg.cc/m2Dpr37H/Captura-de-tela-2026-01-16-124746.png",
    "https://i.postimg.cc/J4nYh3jc/Captura-de-tela-2026-01-16-124750.png",
    "https://i.postimg.cc/yYdpNh0m/Captura-de-tela-2026-01-16-124805.png",
    "https://i.postimg.cc/yYdpNh0h/Captura-de-tela-2026-01-16-124809.png",
    "https://i.postimg.cc/KvzpY7tD/Captura-de-tela-2026-01-16-124813.png",
    "https://i.postimg.cc/Wb3Y4m0X/Captura-de-tela-2026-01-16-124817.png",
    "https://i.postimg.cc/QxtYMgcS/Captura-de-tela-2026-01-16-124822.png",
    "https://i.postimg.cc/Yq9DSNQd/Captura-de-tela-2026-01-16-124827.png",
    "https://i.postimg.cc/gkJt0y3M/Captura-de-tela-2026-01-16-124832.png",
    "https://i.postimg.cc/VLVG0SFB/Captura-de-tela-2026-01-16-124836.png",
    "https://i.postimg.cc/CLQPnZ4C/Captura-de-tela-2026-01-16-124840.png"
  ];

  const logoUrl = "https://i.postimg.cc/bYmQCKWB/MARCADAGUA1.png";
  const whatsappMessage = "Olá! Visitei o site e gostaria de mais informações sobre os valores e horários disponíveis.";
  const whatsappLink = `https://wa.me/5511962826513?text=${encodeURIComponent(whatsappMessage)}`;
  const whatsappPromoMessage = "Olá! Gostaria de aproveitar a oferta exclusiva de Home Care no valor promocional.";
  const whatsappPromoLink = `https://wa.me/5511962826513?text=${encodeURIComponent(whatsappPromoMessage)}`;

  return (
    <div className="font-sans text-gray-800 bg-[#FFFDF7] antialiased selection:bg-[#BAE1FF] selection:text-gray-900 pb-24 md:pb-0">
      
      {/* --- NAVBAR --- */}
      <nav className={`fixed w-full z-50 transition-all duration-300 ${scrolled ? 'bg-white/95 backdrop-blur-md shadow-md py-2 md:py-3' : 'bg-transparent py-4 md:py-6'}`}>
        <div className="max-w-7xl mx-auto px-4 sm:px-6 flex justify-between items-center">
          
          <div className="flex items-center gap-2">
            <img 
              src={logoUrl} 
              alt="Mommy's Baby Care" 
              className="h-12 md:h-16 w-auto object-contain"
              onError={(e) => {
                e.target.onerror = null; 
                e.target.style.display = 'none'; 
                e.target.parentNode.innerHTML += '<span class="font-serif text-xl font-bold text-[#FFB7C5]">Mommy\'s Baby Care</span>';
              }}
            />
          </div>

          <div className="hidden md:flex items-center gap-8 bg-white/60 px-8 py-3 rounded-full border border-[#BAE1FF] backdrop-blur-sm shadow-sm">
            {['O Método', 'Serviços', 'Galeria', 'Info', 'Dúvidas'].map((item) => (
              <a 
                key={item} 
                href={`#${item.toLowerCase().replace(' ', '-').replace('ó','o').replace('ú','u')}`}
                className="text-sm font-bold text-gray-700 hover:text-[#FFB7C5] transition-colors uppercase tracking-wide"
              >
                {item}
              </a>
            ))}
          </div>

          <div className="hidden md:block">
            <a 
              href={whatsappLink}
              target="_blank"
              rel="noopener noreferrer"
              className="bg-[#FFB7C5] hover:bg-[#ffacc0] text-white px-6 py-3 rounded-2xl font-bold shadow-lg shadow-rose-100 transition-all transform hover:-translate-y-1 flex items-center gap-2"
            >
              <MessageCircle size={18} />
              Agendar
            </a>
          </div>

          {/* Botão Mobile Aumentado */}
          <button onClick={() => setIsMenuOpen(!isMenuOpen)} className="md:hidden text-gray-700 bg-white p-3 rounded-xl shadow-sm border border-[#BAE1FF] active:bg-gray-50">
            {isMenuOpen ? <X size={24} /> : <Menu size={24} />}
          </button>
        </div>

        {/* Mobile Menu Otimizado */}
        {isMenuOpen && (
          <div className="md:hidden absolute top-full left-0 w-full bg-white border-t border-[#BAE1FF] shadow-xl p-4 flex flex-col gap-3 animate-fade-in z-50">
             {['O Método', 'Serviços', 'Galeria', 'Info', 'Dúvidas'].map((item) => (
              <a 
                key={item} 
                href={`#${item.toLowerCase().replace(' ', '-').replace('ó','o').replace('ú','u')}`} 
                onClick={() => setIsMenuOpen(false)} 
                className="text-gray-800 font-bold py-4 border-b border-gray-50 text-center active:bg-gray-50 rounded-lg"
              >
                {item}
              </a>
            ))}
            <a href={whatsappLink} className="bg-[#BAE1FF] text-white text-center py-4 rounded-xl font-bold text-lg shadow-md mt-2">
              Chamar no WhatsApp
            </a>
          </div>
        )}
      </nav>

      {/* --- HERO SECTION --- */}
      <section className="relative pt-28 pb-16 lg:pt-48 lg:pb-32 overflow-hidden">
        {/* Background Shapes */}
        <div className="absolute top-0 right-0 w-[300px] md:w-[600px] h-[300px] md:h-[600px] bg-[#FFB7C5]/20 rounded-full blur-3xl -mr-20 -mt-20 -z-10"></div>
        <div className="absolute bottom-0 left-0 w-[200px] md:w-[400px] h-[200px] md:h-[400px] bg-[#BAE1FF]/30 rounded-full blur-3xl -ml-10 -z-10"></div>

        <div className="max-w-7xl mx-auto px-4 sm:px-6 grid lg:grid-cols-2 gap-10 md:gap-16 items-center">
          {/* Order Mobile: Text First, Image Second */}
          <div className="order-1 lg:order-1 space-y-6 md:space-y-8 text-center lg:text-left">
            <div className="inline-block px-3 py-1.5 md:px-4 md:py-2 bg-white border border-[#BAE1FF] rounded-full shadow-sm mb-2">
              <span className="flex items-center gap-2 text-[#89CFF0] font-bold text-[10px] md:text-xs uppercase tracking-widest">
                <Star size={12} fill="currentColor" /> Especialista em Furo Humanizado
              </span>
            </div>
            
            <h1 className="text-4xl sm:text-5xl lg:text-7xl font-serif text-gray-900 leading-tight">
              O primeiro brinco com <span className="text-[#FFB7C5] font-medium italic">carinho</span>.
            </h1>
            
            <p className="text-lg md:text-xl text-gray-700 leading-relaxed max-w-lg mx-auto lg:mx-0 font-medium">
              Transforme esse momento único em uma memória de amor. Técnica segura, sem dor e no conforto do seu lar.
            </p>

            <div className="flex flex-col sm:flex-row gap-3 justify-center lg:justify-start pt-2">
              <a 
                href={whatsappLink}
                className="bg-[#FFB7C5] hover:bg-[#ffacc0] text-white px-8 py-4 rounded-2xl font-bold text-base md:text-lg shadow-xl shadow-rose-100 transition-all hover:scale-105 active:scale-95"
              >
                Agendar Horário
              </a>
              <a 
                href="#valores" 
                className="bg-white text-gray-700 border-2 border-[#BAE1FF] hover:border-[#89CFF0] px-8 py-4 rounded-2xl font-bold text-base md:text-lg transition-all active:bg-gray-50"
              >
                Ver Valores
              </a>
            </div>

            {/* Badges Mobile Optimized */}
            <div className="grid grid-cols-3 gap-2 pt-4 max-w-md mx-auto lg:mx-0">
              <div className="flex flex-col items-center text-center p-2 md:p-3 bg-white border border-[#BAE1FF]/50 rounded-xl shadow-sm">
                <Award className="text-[#FFB7C5] mb-1" size={20} />
                <span className="text-[10px] font-bold text-gray-700 leading-tight">Especialista<br/>Certificada</span>
              </div>
              <div className="flex flex-col items-center text-center p-2 md:p-3 bg-white border border-[#BAE1FF]/50 rounded-xl shadow-sm">
                <ShieldCheck className="text-[#89CFF0] mb-1" size={20} />
                <span className="text-[10px] font-bold text-gray-700 leading-tight">Material 100%<br/>Estéril</span>
              </div>
              <div className="flex flex-col items-center text-center p-2 md:p-3 bg-white border border-[#BAE1FF]/50 rounded-xl shadow-sm">
                <Smile className="text-[#FFB7C5] mb-1" size={20} />
                <span className="text-[10px] font-bold text-gray-700 leading-tight">Técnica<br/>Sem Dor</span>
              </div>
            </div>

            <div className="pt-2 flex items-center justify-center lg:justify-start gap-4 text-xs md:text-sm font-bold text-gray-600">
              <span className="flex items-center gap-1"><CheckCircle size={14} className="text-[#BAE1FF] fill-[#BAE1FF] text-white" /> Atendemos Mogi & Santos</span>
            </div>
          </div>

          <div className="order-2 lg:order-2 relative px-4 md:px-0">
            <div className="relative z-10 rounded-[2rem] md:rounded-[3rem] overflow-hidden shadow-2xl border-4 md:border-8 border-white rotate-2 hover:rotate-0 transition-transform duration-500">
               <img 
                src="https://i.postimg.cc/ydc7g49R/Captura-de-tela-2026-01-16-121317.png" 
                alt="Momento Carinho Mãe e Bebê" 
                className="w-full h-[400px] md:h-[550px] object-cover"
              />
            </div>
            {/* Decoração Flutuante (Escondida em telas muito pequenas para não poluir) */}
            <div className="absolute -bottom-4 -left-4 md:-bottom-8 md:-left-8 bg-white p-4 md:p-6 rounded-3xl shadow-xl border border-[#BAE1FF] animate-bounce-slow hidden sm:block z-20">
               <div className="flex items-center gap-3">
                 <div className="bg-[#E0F2FF] p-2 md:p-3 rounded-full text-[#89CFF0]">
                   <ShieldCheck size={20} />
                 </div>
                 <div>
                   <p className="font-bold text-gray-900 text-sm md:text-lg">Segurança Total</p>
                   <p className="text-gray-600 text-[10px] md:text-xs font-bold">Protocolo ANVISA</p>
                 </div>
               </div>
            </div>
          </div>
        </div>
      </section>

      {/* --- SOBRE A RAQUEL --- */}
      <section id="o-metodo" className="py-16 md:py-24 bg-white relative">
        <div className="max-w-6xl mx-auto px-4 sm:px-6">
          <div className="bg-[#FFF0F5] rounded-[2.5rem] p-6 md:p-16 flex flex-col md:flex-row items-center gap-8 md:gap-12 relative overflow-hidden shadow-sm">
            <div className="absolute top-0 right-0 w-64 h-64 bg-[#BAE1FF]/20 rounded-full blur-3xl"></div>

            <div className="md:w-1/3 text-center">
              <div className="w-40 h-40 md:w-48 md:h-48 mx-auto bg-white rounded-full p-2 shadow-lg mb-4 md:mb-6 rotate-3 border-4 border-white">
                <img src="https://i.postimg.cc/Jnftv53k/Captura-de-tela-2026-01-16-121104.png" alt="Raquel" className="w-full h-full rounded-full object-cover" />
              </div>
              <h3 className="font-serif text-2xl font-bold text-gray-900">Raquel</h3>
              <p className="text-[#FFB7C5] font-bold text-sm">Especialista Certificada</p>
            </div>

            <div className="md:w-2/3">
              <h2 className="text-2xl md:text-3xl font-serif font-bold text-gray-900 mb-4 md:mb-6 text-center md:text-left">Muito prazer, mamãe!</h2>
              <p className="text-base md:text-lg text-gray-800 leading-relaxed mb-6 font-medium text-center md:text-left">
                "Minha missão é garantir que o primeiro brinquinho seja uma lembrança doce. Utilizo técnicas avançadas como o <strong>Ponto Neutro (Acupuntura)</strong> e <strong>Laserterapia</strong> para reduzir o desconforto a zero."
              </p>
              
              <div className="grid grid-cols-2 gap-3 md:gap-4">
                <div className="bg-white p-3 md:p-4 rounded-2xl flex flex-col md:flex-row items-center gap-2 md:gap-3 shadow-sm border border-[#BAE1FF]/30 text-center md:text-left">
                  <Sparkles className="text-[#BAE1FF]" size={20} />
                  <span className="font-bold text-gray-800 text-xs md:text-sm">Laserterapia</span>
                </div>
                <div className="bg-white p-3 md:p-4 rounded-2xl flex flex-col md:flex-row items-center gap-2 md:gap-3 shadow-sm border border-[#FFB7C5]/30 text-center md:text-left">
                  <Baby className="text-[#FFB7C5]" size={20} />
                  <span className="font-bold text-gray-800 text-xs md:text-sm">Sem Pistola</span>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      {/* --- ESTATÍSTICAS DINÂMICAS --- */}
      <section className="relative py-16 md:py-20 overflow-hidden bg-gradient-to-r from-[#FFB7C5] to-[#BAE1FF] text-white">
        <div className="absolute inset-0 opacity-20" style={{backgroundImage: "radial-gradient(circle, #fff 10%, transparent 10%)", backgroundSize: "20px 20px"}}></div>

        <div className="max-w-7xl mx-auto px-4 sm:px-6 relative z-10">
          <div className="grid grid-cols-2 md:grid-cols-4 gap-4 md:gap-8">
            
            <div className="bg-white/20 backdrop-blur-md p-4 md:p-6 rounded-2xl border border-white/30 text-center">
              <div className="w-10 h-10 md:w-12 md:h-12 bg-white text-[#FFB7C5] rounded-full flex items-center justify-center mx-auto mb-3 shadow-lg">
                 <Baby size={24} />
              </div>
              <div className="text-3xl md:text-5xl font-bold mb-1 font-serif flex justify-center text-gray-900">
                +<AnimatedNumber end={1000} />
              </div>
              <p className="text-gray-800 text-[10px] md:text-sm font-bold uppercase tracking-widest">Bebês Atendidos</p>
            </div>

            <div className="bg-white/20 backdrop-blur-md p-4 md:p-6 rounded-2xl border border-white/30 text-center">
              <div className="w-10 h-10 md:w-12 md:h-12 bg-white text-[#BAE1FF] rounded-full flex items-center justify-center mx-auto mb-3 shadow-lg">
                 <Heart size={24} />
              </div>
              <div className="text-3xl md:text-5xl font-bold mb-1 font-serif flex justify-center text-gray-900">
                <AnimatedNumber end={100} suffix="%" />
              </div>
              <p className="text-gray-800 text-[10px] md:text-sm font-bold uppercase tracking-widest">Humanizado</p>
            </div>

            <div className="bg-white/20 backdrop-blur-md p-4 md:p-6 rounded-2xl border border-white/30 text-center">
              <div className="w-10 h-10 md:w-12 md:h-12 bg-white text-[#FFB7C5] rounded-full flex items-center justify-center mx-auto mb-3 shadow-lg">
                 <Star size={24} />
              </div>
              <div className="text-3xl md:text-5xl font-bold mb-1 font-serif flex justify-center text-gray-900">
                5.0
              </div>
              <div className="flex justify-center gap-0.5 text-amber-300 mb-1">
                 {[...Array(5)].map((_, i) => <Star key={i} size={10} fill="currentColor" />)}
              </div>
              <p className="text-gray-800 text-[10px] md:text-sm font-bold uppercase tracking-widest">Avaliação Google</p>
            </div>

            <div className="bg-white/20 backdrop-blur-md p-4 md:p-6 rounded-2xl border border-white/30 text-center">
               <div className="w-10 h-10 md:w-12 md:h-12 bg-white text-[#BAE1FF] rounded-full flex items-center justify-center mx-auto mb-3 shadow-lg">
                 <ShieldCheck size={24} />
              </div>
              <div className="text-3xl md:text-5xl font-bold mb-1 font-serif flex justify-center text-gray-900">
                <AnimatedNumber end={0} suffix="%" />
              </div>
              <p className="text-gray-800 text-[10px] md:text-sm font-bold uppercase tracking-widest">Trauma ou Dor</p>
            </div>

          </div>
        </div>
      </section>

      {/* --- SERVIÇOS --- */}
      <section id="servicos" className="py-16 md:py-24 bg-[#FFFDF7]">
        <div className="max-w-7xl mx-auto px-4 sm:px-6">
          <div className="text-center mb-12 md:mb-16">
            <h2 className="text-3xl md:text-4xl font-serif font-bold text-gray-900 mb-4">Nossos Serviços</h2>
            <div className="w-20 h-1 bg-[#BAE1FF] mx-auto rounded-full"></div>
          </div>

          <div className="grid md:grid-cols-3 gap-6">
            {[
              { title: "Primeiro Brinquinho", desc: "Técnica humanizada exclusiva para recém-nascidos. Sem dor traumática e com joias estéreis.", icon: <Baby size={28} /> },
              { title: "Body Piercing & Adultos", desc: "Realize seu desejo de ter novos furos ou piercings com total biossegurança e joias de titânio ou ouro 18k.", icon: <Sparkles size={28} /> },
              { title: "Consultoria Materna", desc: "Apoio especializado em aleitamento e cuidados com o recém-nascido.", icon: <Heart size={28} /> }
            ].map((s, i) => (
              <div key={i} className="bg-white p-6 md:p-8 rounded-[2rem] hover:shadow-xl transition-shadow border border-[#BAE1FF]/20 group">
                <div className="w-14 h-14 bg-[#E0F2FF] rounded-2xl flex items-center justify-center text-[#89CFF0] mb-4 md:mb-6 group-hover:bg-[#BAE1FF] group-hover:text-white transition-colors">
                  {s.icon}
                </div>
                <h3 className="text-lg md:text-xl font-bold text-gray-900 mb-3">{s.title}</h3>
                <p className="text-gray-700 leading-relaxed mb-6 font-medium text-sm md:text-base">{s.desc}</p>
                <a href={whatsappLink} className="text-[#FFB7C5] font-bold text-sm uppercase tracking-wide hover:underline">Saiba Mais</a>
              </div>
            ))}
          </div>
        </div>
      </section>

      {/* --- PROMOÇÃO HOME CARE --- */}
      <section id="valores" className="py-16 md:py-20 bg-white">
        <div className="max-w-4xl mx-auto px-4 sm:px-6">
          <div className="relative bg-gradient-to-br from-[#FFB7C5] to-[#BAE1FF] rounded-[2rem] p-1 shadow-2xl overflow-hidden">
            <div className="absolute inset-0 opacity-20" style={{backgroundImage: "radial-gradient(#fff 2px, transparent 2px)", backgroundSize: "30px 30px"}}></div>

            <div className="bg-white rounded-[1.8rem] p-6 md:p-12 h-full relative overflow-hidden">
              <div className="absolute top-0 right-0 bg-[#BAE1FF] text-white text-[10px] md:text-xs font-bold px-4 py-2 rounded-bl-2xl uppercase tracking-widest shadow-md">
                Oferta Exclusiva
              </div>

              <div className="flex flex-col md:flex-row gap-8 md:gap-12 items-center">
                <div className="flex-1 space-y-4 md:space-y-6 text-center md:text-left">
                   <div className="inline-block bg-[#E0F2FF] text-[#89CFF0] px-3 py-1 rounded-full text-xs font-bold border border-[#BAE1FF]">
                     <span className="flex items-center gap-1"><MapPin size={12}/> Atendimento Domiciliar</span>
                   </div>
                   
                   <h2 className="text-2xl md:text-3xl font-serif font-bold text-gray-900">
                     O Studio vai até você!
                   </h2>
                   <p className="text-gray-700 font-medium text-sm md:text-base">
                     Válido para <strong>Mogi das Cruzes</strong> (Centro e Região) e <strong>Santos</strong>.
                   </p>

                   <ul className="space-y-2 pt-2 text-left inline-block">
                     <li className="flex items-center gap-3 text-gray-800 font-bold text-sm">
                       <div className="bg-green-100 p-1 rounded-full"><CheckCircle size={12} className="text-green-600"/></div>
                       Sinal de 20% para reserva
                     </li>
                     <li className="flex items-center gap-3 text-gray-800 font-bold text-sm">
                       <div className="bg-green-100 p-1 rounded-full"><CheckCircle size={12} className="text-green-600"/></div>
                       Pagamento Promocional no PIX
                     </li>
                   </ul>
                </div>

                <div className="flex-none bg-[#FFF0F5] p-6 rounded-3xl border border-[#FFB7C5]/30 text-center w-full md:w-auto min-w-[260px]">
                   <p className="text-gray-500 text-xs line-through font-bold">De R$ 150,00</p>
                   <div className="text-4xl md:text-5xl font-bold text-[#FFB7C5] my-1">R$ 130</div>
                   <p className="text-gray-600 text-xs mb-4 font-bold">por procedimento</p>
                   
                   <div className="border-t border-stone-200 pt-4 mb-4">
                     <p className="font-bold text-gray-800 text-sm">Joia Baby (Par)</p>
                     <p className="text-lg font-serif text-[#89CFF0]">R$ 89,90</p>
                     <p className="text-[10px] text-gray-500 font-bold">Aço ou Ouro 24k</p>
                   </div>

                   <a href={whatsappPromoLink} target="_blank" rel="noopener noreferrer" className="block w-full bg-[#89CFF0] hover:bg-[#72bcd4] text-white font-bold py-3 rounded-xl shadow-lg shadow-blue-100 transition-transform hover:-translate-y-1 active:scale-95">
                     Quero Aproveitar
                   </a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      {/* --- HALL DA FOFURA (GALERIA) --- */}
      <section id="galeria" className="py-16 md:py-24 bg-[#FFFDF7] overflow-hidden">
        <div className="max-w-7xl mx-auto px-4 mb-8 text-center">
          <div className="inline-block bg-[#E0F2FF] text-[#89CFF0] px-4 py-1 rounded-full text-xs font-bold uppercase tracking-widest mb-4">
             Resultados Reais
          </div>
          <h2 className="text-3xl md:text-4xl font-serif font-bold text-gray-900">Hall da Fofura</h2>
          <p className="text-gray-700 mt-2 md:mt-4 font-medium text-sm md:text-base">Alguns dos sorrisos que já atendemos com muito amor.</p>
        </div>

        <div 
          ref={scrollRef}
          className="flex overflow-x-auto gap-4 md:gap-6 px-4 md:px-6 pb-8 scrollbar-hide max-w-[100vw]"
          style={{scrollbarWidth: 'none', msOverflowStyle: 'none'}}
          onMouseEnter={() => setIsPaused(true)} 
          onMouseLeave={() => setIsPaused(false)} 
          onTouchStart={() => setIsPaused(true)}
          onTouchEnd={() => setIsPaused(false)}
        >
          {galleryImages.map((img, i) => (
            <div 
              key={i} 
              className="flex-none w-64 md:w-80 bg-white p-3 shadow-lg rounded-2xl transform transition-transform duration-300"
            >
              <div className="w-full h-64 md:h-80 rounded-xl overflow-hidden bg-[#FFF0F5]">
                <img 
                  src={img} 
                  alt={`Bebê Fofo ${i+1}`} 
                  className="w-full h-full object-cover hover:opacity-90 transition-opacity"
                  loading="lazy"
                />
              </div>
              <div className="text-center pt-3 pb-1">
                <Heart size={16} className="text-[#FFB7C5] mx-auto fill-current" />
              </div>
            </div>
          ))}
          
          <div className="flex-none w-64 md:w-80 bg-[#FFF0F5] p-8 shadow-inner rounded-2xl flex flex-col justify-center items-center text-center">
             <div className="bg-white p-4 rounded-full mb-4 shadow-sm">
               <Instagram className="text-[#FFB7C5]" size={32} />
             </div>
             <h3 className="font-bold text-gray-800 text-lg mb-2">Quer ver mais?</h3>
             <a 
               href="https://instagram.com/mommysbabycare" 
               target="_blank" 
               rel="noopener noreferrer"
               className="bg-[#FFB7C5] text-white px-6 py-2 rounded-full font-bold text-sm hover:bg-[#ffacc0] transition-colors"
             >
               @mommysbabycare
             </a>
          </div>
        </div>
      </section>

      {/* --- PORTFÓLIO & INFORMAÇÕES (CARROSSEL AUTOMÁTICO) --- */}
      <section id="info" className="py-16 md:py-24 bg-white border-t border-[#BAE1FF]/30 overflow-hidden">
        <div className="max-w-7xl mx-auto px-4 mb-8 text-center">
          <div className="inline-block bg-[#E0F2FF] text-[#89CFF0] px-4 py-1 rounded-full text-xs font-bold uppercase tracking-widest mb-4">
             Informações Detalhadas
          </div>
          <h2 className="text-3xl md:text-4xl font-serif font-bold text-gray-900">Portfólio & Materiais</h2>
          <p className="text-gray-700 mt-2 md:mt-4 max-w-2xl mx-auto font-medium text-sm md:text-base">
            Confira detalhes sobre procedimentos, materiais e cuidados. Deslize para ver mais.
          </p>
        </div>

        <div 
          ref={infoScrollRef}
          className="flex overflow-x-auto gap-4 md:gap-6 px-4 md:px-6 pb-8 scrollbar-hide max-w-[100vw]"
          style={{scrollbarWidth: 'none', msOverflowStyle: 'none'}}
          onMouseEnter={() => setIsInfoPaused(true)} 
          onMouseLeave={() => setIsInfoPaused(false)} 
          onTouchStart={() => setIsInfoPaused(true)}
          onTouchEnd={() => setIsInfoPaused(false)}
        >
          {portfolioImages.map((img, i) => (
            <div key={i} className="flex-none w-64 md:w-80 group relative overflow-hidden rounded-2xl shadow-lg border border-gray-100">
              <div className="h-80 md:h-96 bg-gray-50">
                <img 
                  src={img} 
                  alt={`Informação Portfólio ${i+1}`} 
                  className="w-full h-full object-cover"
                  loading="lazy"
                />
              </div>
              <div className="absolute inset-0 bg-gradient-to-t from-black/60 via-transparent to-transparent opacity-0 group-hover:opacity-100 transition-opacity flex items-end justify-center p-6">
                <span className="text-white font-bold flex items-center gap-2 text-sm">
                  <ImageIcon size={16} /> Ver Detalhes
                </span>
              </div>
            </div>
          ))}
        </div>
      </section>

      {/* --- FAQ --- */}
      <section id="duvidas" className="py-16 md:py-24 bg-[#FFFDF7]">
        <div className="max-w-3xl mx-auto px-4 sm:px-6">
          <h2 className="text-3xl font-serif font-bold text-center text-gray-900 mb-8 md:mb-12">Perguntas Frequentes</h2>
          <div className="space-y-3">
            {faqs.map((f, i) => (
              <div key={i} className="bg-white rounded-2xl shadow-sm border border-stone-100 overflow-hidden">
                <button 
                  onClick={() => toggleFaq(i)}
                  className="w-full flex justify-between items-center p-5 md:p-6 text-left font-bold text-gray-800 hover:text-[#FFB7C5] transition-colors text-sm md:text-base"
                >
                  {f.q}
                  {openFaq === i ? <ChevronUp className="text-[#FFB7C5] shrink-0"/> : <ChevronDown className="text-[#BAE1FF] shrink-0"/>}
                </button>
                {openFaq === i && (
                  <div className="p-5 md:p-6 pt-0 text-gray-700 text-sm md:text-base leading-relaxed border-t border-stone-200/50">
                    {f.a}
                  </div>
                )}
              </div>
            ))}
          </div>
        </div>
      </section>

      {/* --- DEPOIMENTOS --- */}
      <section id="depoimentos" className="py-16 md:py-24 bg-[#FFB7C5] text-white">
        <div className="max-w-7xl mx-auto px-4 sm:px-6">
          <div className="text-center mb-12">
            <h2 className="text-3xl font-serif font-bold mb-4 text-gray-900">Mamães que Confiam</h2>
            <div className="flex justify-center gap-1">
              {[1,2,3,4,5].map(i => <Star key={i} className="fill-current text-[#FFFDF7]" size={20} />)}
            </div>
          </div>

          <div className="grid md:grid-cols-3 gap-6">
            {testimonials.map((t, i) => (
              <div key={i} className="bg-white/90 backdrop-blur-md p-6 rounded-3xl border border-white/50 shadow-lg">
                 <div className="flex items-center gap-4 mb-4">
                   <div className="w-10 h-10 bg-[#FFB7C5] text-white rounded-full flex items-center justify-center font-bold text-lg shrink-0">
                     {t.name.charAt(0)}
                   </div>
                   <div>
                     <p className="font-bold text-gray-900 text-sm">{t.name}</p>
                     <p className="text-[10px] text-gray-500 uppercase tracking-wide font-bold">Cliente Verificada</p>
                   </div>
                 </div>
                 <p className="italic text-gray-700 leading-relaxed font-medium text-sm">"{t.text}"</p>
              </div>
            ))}
          </div>
          
          <div className="text-center mt-10">
            <a href="https://www.google.com/search?q=mommys+baby+care+mogi" target="_blank" rel="noopener noreferrer" className="inline-block bg-white text-[#FFB7C5] px-8 py-3 rounded-full font-bold shadow-lg hover:shadow-xl transition-all text-sm">
              Ver Avaliações no Google
            </a>
          </div>
        </div>
      </section>

      {/* --- FOOTER --- */}
      <footer className="bg-white pt-16 pb-24 md:pb-10 border-t border-[#BAE1FF]/50">
        <div className="max-w-6xl mx-auto px-6 grid md:grid-cols-4 gap-8 text-sm text-stone-500">
          
          <div className="col-span-1 md:col-span-1">
             <img src={logoUrl} alt="Logo Footer" className="h-10 w-auto mb-4 opacity-80" />
             <p className="mb-4 text-gray-600 font-medium">Cuidando do seu maior tesouro com amor, técnica e segurança.</p>
             <div className="flex gap-4">
               <a href="https://instagram.com/mommysbabycare" className="w-10 h-10 bg-[#FFF0F5] rounded-full flex items-center justify-center text-[#FFB7C5] hover:bg-[#FFB7C5] hover:text-white transition-all"><Instagram size={20}/></a>
               <a href="mailto:contato.mommysbaby@gmail.com" className="w-10 h-10 bg-[#E0F2FF] rounded-full flex items-center justify-center text-[#89CFF0] hover:bg-[#89CFF0] hover:text-white transition-all"><MessageCircle size={20}/></a>
             </div>
          </div>

          <div className="space-y-4">
             <h4 className="font-bold text-gray-900 uppercase tracking-widest text-xs">Onde Estamos</h4>
             <ul className="space-y-4">
               <li className="flex gap-3">
                 <MapPin className="text-[#FFB7C5] shrink-0" size={18} />
                 <span className="text-gray-700"><strong>Mogi das Cruzes:</strong><br/>R. Barão de Jaceguai, 788</span>
               </li>
               <li className="flex gap-3">
                 <MapPin className="text-[#89CFF0] shrink-0" size={18} />
                 <span className="text-gray-700"><strong>Santos:</strong><br/>Ilha Porchat (Home Care)</span>
               </li>
             </ul>
          </div>

          <div className="md:col-span-2">
            <h4 className="font-bold text-gray-900 uppercase tracking-widest text-xs mb-4">Links Rápidos</h4>
            <div className="grid grid-cols-2 gap-2">
              <a href="#o-metodo" className="text-gray-700 hover:text-[#FFB7C5]">O Método</a>
              <a href="#servicos" className="text-gray-700 hover:text-[#FFB7C5]">Serviços</a>
              <a href="#valores" className="text-gray-700 hover:text-[#FFB7C5]">Investimento</a>
              <a href="#duvidas" className="text-gray-700 hover:text-[#FFB7C5]">Dúvidas</a>
            </div>
          </div>

        </div>
        
        <div className="max-w-6xl mx-auto px-6 mt-12 pt-8 border-t border-stone-100 text-center text-xs text-gray-500 font-medium">
          <p>&copy; 2026 Mommy's Baby Care. Todos os direitos reservados.</p>
        </div>
      </footer>

      {/* --- BARRA FIXA MOBILE (WHATSAPP FLUTUANTE) --- */}
      <div className="md:hidden fixed bottom-0 left-0 w-full bg-white/90 backdrop-blur-md border-t border-gray-100 p-4 z-50 shadow-[0_-5px_20px_rgba(0,0,0,0.1)] flex items-center justify-between gap-4 pb-6">
        <div className="flex flex-col">
          <span className="text-[10px] text-gray-500 font-bold uppercase tracking-wider">Fale Conosco</span>
          <span className="text-sm font-bold text-gray-900">Agende seu horário</span>
        </div>
        <a 
          href={whatsappLink}
          target="_blank"
          rel="noopener noreferrer"
          className="bg-[#25D366] hover:bg-[#20b858] text-white px-6 py-3 rounded-xl font-bold text-sm shadow-lg flex items-center gap-2 animate-pulse"
        >
          <MessageCircle size={20} />
          WhatsApp
        </a>
      </div>
    </div>
  );
};

export default App;