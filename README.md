import { Github, Linkedin, Mail, ArrowUpRight } from "lucide-react";

export default function Hero() {
  return (
    <section className="min-h-[80vh] flex flex-col justify-center max-w-4xl mx-auto px-6 py-20">
      <div className="inline-block px-3 py-1 mb-4 text-xs font-medium text-emerald-400 bg-emerald-950/50 border border-emerald-800/50 rounded-full w-fit">
        Available for work
      </div>
      <h1 className="text-4xl md:text-6xl font-bold tracking-tight text-white mb-4">
        Hi, I'm <span className="text-indigo-400">Your Name</span> 👋
      </h1>
      <p className="text-lg md:text-xl text-zinc-400 mb-8 max-w-2xl leading-relaxed">
        Frontend / Full Stack Developer passionate about building fast, responsive, and user-centric web applications.
      </p>
      
      <div className="flex flex-wrap gap-4 items-center">
        <a href="#projects" className="px-6 py-3 bg-white text-black font-medium rounded-lg hover:bg-zinc-200 transition">
          View Projects
        </a>
        <a href="mailto:your@email.com" className="px-6 py-3 border border-zinc-700 font-medium rounded-lg text-white hover:bg-zinc-900 transition flex items-center gap-2">
          Contact Me <ArrowUpRight size={18} />
        </a>
      </div>
    </section>
  );
}
