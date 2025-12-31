export default function Home() {
  return (
    <main className="min-h-screen bg-white text-gray-900">
      {/* Header */}
      <header className="flex justify-between items-center px-6 py-4 shadow-sm">
        <h1 className="text-xl font-bold">Excellerate Group Of Companies</h1>
        <nav className="space-x-4 text-sm">
          <a href="#about">About</a>
          <a href="#services">Services</a>
          <a href="#contact">Contact</a>
        </nav>
      </header>

      {/* Hero Section */}
      <section className="px-6 py-20 text-center bg-gray-50">
        <h2 className="text-4xl font-extrabold mb-4">
          Driving Growth. Building Excellence.
        </h2>
        <p className="max-w-2xl mx-auto text-lg text-gray-600 mb-6">
          Excellerate Group Of Companies is a diversified business group focused on innovation, technology, consulting, and scalable digital solutions.
        </p>
        <div className="space-x-4">
          <button className="px-6 py-3 bg-black text-white rounded-lg">
            Explore Our Services
          </button>
          <button className="px-6 py-3 border rounded-lg">
            Partner With Us
          </button>
        </div>
      </section>

      {/* About Section */}
      <section id="about" className="px-6 py-16 max-w-4xl mx-auto">
        <h3 className="text-2xl font-bold mb-4">About Us</h3>
        <p className="text-gray-700 leading-relaxed">
          Excellerate Group Of Companies is built to incubate, manage, and scale high-impact ventures across multiple industries. We empower individuals, startups, and enterprises with modern solutions designed for sustainable growth.
        </p>
      </section>

      {/* Services Section */}
      <section id="services" className="px-6 py-16 bg-gray-50">
        <h3 className="text-2xl font-bold text-center mb-10">Our Services</h3>
        <div className="grid gap-6 md:grid-cols-2 max-w-5xl mx-auto">
          <div className="p-6 bg-white rounded-xl shadow">
            <h4 className="font-semibold mb-2">Digital Marketplace Solutions</h4>
            <p className="text-sm text-gray-600">Sell digital products, courses, and services with ease.</p>
          </div>
          <div className="p-6 bg-white rounded-xl shadow">
            <h4 className="font-semibold mb-2">Business Consulting</h4>
            <p className="text-sm text-gray-600">Strategy, growth planning, and operational excellence.</p>
          </div>
          <div className="p-6 bg-white rounded-xl shadow">
            <h4 className="font-semibold mb-2">Technology & Software</h4>
            <p className="text-sm text-gray-600">Web platforms, SaaS products, and automation.</p>
          </div>
          <div className="p-6 bg-white rounded-xl shadow">
            <h4 className="font-semibold mb-2">Training & Capacity Building</h4>
            <p className="text-sm text-gray-600">Courses, workshops, and mentorship programs.</p>
          </div>
        </div>
      </section>

      {/* Contact Section */}
      <section id="contact" className="px-6 py-16 text-center">
        <h3 className="text-2xl font-bold mb-4">Let’s Work Together</h3>
        <p className="text-gray-600 mb-6">
          Ready to grow with Excellerate Group Of Companies?
        </p>
        <button className="px-6 py-3 bg-black text-white rounded-lg">
          Contact Us
        </button>
      </section>

      {/* Footer */}
      <footer className="px-6 py-6 text-center text-sm text-gray-500 border-t">
        © {new Date().getFullYear()} Excellerate Group Of Companies. All rights reserved.
      </footer>
    </main>
  );
}
