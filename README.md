import Head from 'next/head';

export default function Home() {
  return (
    <div className="min-h-screen bg-gradient-to-r from-blue-100 to-blue-200">
      <Head>
        <title>Beautiful Website</title>
      </Head>

      {/* Hero Section */}
      <section className="text-center py-20">
        <h1 className="text-5xl font-bold text-gray-800">
          Welcome to My Beautiful Website
        </h1>
        <p className="text-lg mt-4 text-gray-600">
          Discover amazing features and seamless design.
        </p>
        <button className="mt-8 px-6 py-3 bg-blue-600 text-white rounded-lg shadow-md hover:bg-blue-700">
          Get Started
        </button>
      </section>

      {/* Features Section */}
      <section className="py-16">
        <div className="container mx-auto px-6">
          <div className="flex flex-wrap">
            <div className="w-full md:w-1/3 p-4">
              <div className="bg-white p-6 rounded-lg shadow-lg text-center">
                <h3 className="text-2xl font-semibold text-gray-800">
                  Feature 1
                </h3>
                <p className="mt-2 text-gray-600">
                  Description of the first amazing feature.
                </p>
              </div>
            </div>

            <div className="w-full md:w-1/3 p-4">
              <div className="bg-white p-6 rounded-lg shadow-lg text-center">
                <h3 className="text-2xl font-semibold text-gray-800">
                  Feature 2
                </h3>
                <p className="mt-2 text-gray-600">
                  Description of the second amazing feature.
                </p>
              </div>
            </div>

            <div className="w-full md:w-1/3 p-4">
              <div className="bg-white p-6 rounded-lg shadow-lg text-center">
                <h3 className="text-2xl font-semibold text-gray-800">
                  Feature 3
                </h3>
                <p className="mt-2 text-gray-600">
                  Description of the third amazing feature.
                </p>
              </div>
            </div>
          </div>
        </div>
      </section>

      {/* Footer */}
      <footer className="bg-blue-600 text-white text-center py-6">
        <p>© 2024 My Beautiful Website</p>
      </footer>
    </div>
  );
}
