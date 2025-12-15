
import { motion } from "framer-motion";
whileInView="visible"
viewport={{ once: true }}
transition={{ duration: 0.8 }}
className="max-w-4xl mx-auto bg-white/40 backdrop-blur-xl rounded-3xl shadow-2xl p-10 mb-12 border border-white/30"
>
<h2 className="text-3xl font-bold text-pink-600 mb-6 flex items-center gap-2">
<Server /> Backend Ready
</h2>
<ul className="space-y-3 text-lg">
<li>✔ Scalable structure for Node.js & Express</li>
<li>✔ API-ready frontend architecture</li>
<li>✔ Easy MongoDB / SQL integration</li>
<li>✔ Perfect for real-world full stack projects</li>
</ul>
</motion.section>


{/* Career */}
<motion.section
variants={fadeUp}
initial="hidden"
whileInView="visible"
viewport={{ once: true }}
transition={{ duration: 0.8 }}
className="max-w-4xl mx-auto bg-white/40 backdrop-blur-xl rounded-3xl shadow-2xl p-10 mb-20 border border-white/30"
>
<h2 className="text-3xl font-bold text-pink-600 mb-6">Career Focus</h2>
<p className="text-lg">
This portfolio is designed to impress <b>recruiters</b>,
<b> internship coordinators</b>, and <b>placement panels</b> with clean
UI, smooth animations, and scalable full stack architecture.
</p>
</motion.section>


{/* Footer */}
<motion.footer
initial={{ opacity: 0 }}
animate={{ opacity: 1 }}
transition={{ delay: 0.5 }}
className="text-center pb-10"
>
<p className="flex justify-center gap-2 items-center mb-4">
<Code2 /> Built with React, Tailwind & Framer Motion
</p>
<div className="flex justify-center gap-4">
<a
href="https://github.com/khushimishra"
className="inline-flex items-center gap-2 px-6 py-3 bg-pink-600 text-white rounded-full shadow-lg hover:bg-pink-700"
>
<Github /> GitHub
</a>
<button className="inline-flex items-center gap-2 px-6 py-3 bg-white/60 backdrop-blur rounded-full shadow-lg hover:bg-white">
<FileText /> Resume
</button>
</div>
</motion.footer>
</div>
);
}
