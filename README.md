<!DOCTYPE html>
<html>
<head>
<title>Background Image Example</title>
<style>
  body {
    background-image: url('./image\ copy\ 7.png'); 
    background-repeat: no-repeat; 
    background-size: cover; 
    background-position: center; 
  }
</style>
</head>
<body>
<div className="min-h-screen flex items-center justify-center p-4 relative overflow-hidden">
      <div className="absolute inset-0 bg-gradient-to-br from-blue-900 via-purple-900 to-indigo-900 opacity-50">
        <div className="absolute inset-0">
          <div className="absolute top-20 left-20 w-2 h-2 bg-white rounded-full opacity-20 animate-ping"></div>
          <div className="absolute top-1/2 right-1/4 w-1 h-1 bg-cyan-300 rounded-full opacity-30 animate-ping delay-1000"></div>
          <div className="absolute bottom-20 left-1/3 w-3 h-3 bg-purple-300 rounded-full opacity-15 animate-ping delay-2000"></div>
          <div className="absolute bottom-1/4 right-20 w-2 h-2 bg-white rounded-full opacity-25 animate-ping delay-3000"></div>
        </div>
      </div>
      <div className="relative w-full max-w-4xl bg-white/95 backdrop-blur-sm border border-white/20 rounded-xl shadow-2xl overflow-hidden z-10">
        <div className="bg-gradient-to-r from-primary to-purple-600 text-primary-foreground p-6 text-center relative overflow-hidden">
          <div className="absolute inset-0 bg-black/10"></div>
          <h1 className="text-3xl md:text-5xl font-bold mb-2 relative z-10">TECH INNOVATE 2023</h1>
          <p className="text-lg md:text-xl relative z-10">Where Ideas Become Reality</p>
        </div>
        <div className="p-6 md:p-8">
          <div className="grid grid-cols-1 md:grid-cols-3 gap-6 md:gap-8">
            <div className="space-y-4">
              <div className="bg-white/80 backdrop-blur-sm p-4 rounded-lg shadow-sm">
                <h2 className="text-lg font-semibold text-foreground mb-2">Date & Time</h2>
                <p className="text-muted-foreground">November 15-16, 2023</p>
                <p className="text-muted-foreground">9:00 AM - 6:00 PM Daily</p>
              </div>
              <div className="bg-white/80 backdrop-blur-sm p-4 rounded-lg shadow-sm">
                <h2 className="text-lg font-semibold text-foreground mb-2">Location</h2>
                <p className="text-muted-foreground">Convention Center</p>
                <p className="text-muted-foreground">123 Innovation Drive</p>
                <p className="text-muted-foreground">Tech City, TC 12345</p>
              </div>
            </div>
            <div className="flex flex-col items-center justify-center md:col-span-2">
              <div className="w-full h-48 md:h-64 bg-gradient-to-br from-accent to-blue-500 rounded-lg flex items-center justify-center mb-6 shadow-lg overflow-hidden">
                <img 
                  src="https://images.unsplash.com/photo-1551288049-bebda4e38f71?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2070&q=80" style="height: 100px; width: 100px"
                  alt="Abstract digital visualization representing technology innovation with vibrant colors and geometric patterns"
                  className="w-full h-full object-cover"
                />
              </div>
              <p className="text-center text-foreground mb-6 bg-white/70 px-4 py-2 rounded-lg">
                Join us for two days of inspiring talks, hands-on workshops, and networking with industry leaders in technology and innovation.
              </p>
              <div className="flex gap-4 flex-wrap justify-center">
                <button className="bg-gradient-to-r from-primary to-purple-600 text-primary-foreground px-6 py-3 rounded-md font-semibold hover:from-primary/90 hover:to-purple-500 transition-all shadow-md">
                  Register Now
                </button>
                <button className="border-2 border-primary/50 bg-white/80 px-6 py-3 rounded-md font-medium hover:bg-primary/10 transition-all backdrop-blur-sm">
                  Learn More
                </button>
              </div>
            </div>
          </div>
          <div className="mt-8">
            <h2 className="text-2xl font-bold text-foreground mb-6 text-center">Featured Speakers</h2>
            <div className="grid grid-cols-1 md:grid-cols-3 gap-6">
              <div className="bg-white/80 backdrop-blur-sm p-4 rounded-lg text-center shadow-sm hover:shadow-md transition-shadow">
                <div className="w-20 h-20 mx-auto mb-4 rounded-full overflow-hidden border-2 border-white/50">
                  <img 
                    src="./image copy.png" style="height: 100px; width: 100px"
                    alt="Professional headshot of Sarah Johnson, AI Research Director"
                    className="w-full h-full object-cover"
                  />
                </div>
                <h3 className="font-semibold text-foreground">Sarah Johnson</h3>
                <p className="text-muted-foreground text-sm">AI Research Director</p>
              </div>
              
   <div className="bg-white/80 backdrop-blur-sm p-4 rounded-lg text-center shadow-sm hover:shadow-md transition-shadow">
                <div className="w-20 h-20 mx-auto mb-4 rounded-full overflow-hidden border-2 border-white/50">
                  <img 
                    src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2070&q=80" style="height: 100px; width: 100px"
                    alt="Professional headshot of Michael Chen, Startup Founder"
                    className="w-full h-full object-cover"
                  />
                </div>
                <h3 className="font-semibold text-foreground">Michael Chen</h3>
                <p className="text-muted-foreground text-sm">Startup Founder</p>
              </div>
              
   <div className="bg-white/80 backdrop-blur-sm p-4 rounded-lg text-center shadow-sm hover:shadow-md transition-shadow">
                <div className="w-20 h-20 mx-auto mb-4 rounded-full overflow-hidden border-2 border-white/50">
                  <img 
                    src="https://images.unsplash.com/photo-1438761681033-6461ffad8d80?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2070&q=80" style="height: 100px; width: 100px"
                    alt="Professional headshot of Dr. Emma Rodriguez, Software Architect"
                    className="w-full h-full object-cover"
                  />
                </div>
                <h3 className="font-semibold text-foreground">Dr. Emma Rodriguez</h3>
                <p className="text-muted-foreground text-sm">Software Architect</p>
              </div>
            </div>
          </div>
          <div className="mt-8 bg-white/90 backdrop-blur-sm p-6 rounded-lg shadow-sm">
            <h2 className="text-xl font-bold text-foreground mb-4 text-center">Event Highlights</h2>
            <div className="grid grid-cols-1 md:grid-cols-2 gap-4">
              <div className="flex items-start">
                <div className="bg-gradient-to-r from-primary to-purple-600 text-primary-foreground rounded-full w-8 h-8 flex items-center justify-center mr-3 flex-shrink-0 font-bold shadow-sm">
                  1
                </div>
                <p className="text-foreground">Keynote speeches from industry pioneers</p>
              </div>
              <div className="flex items-start">
                <div className="bg-gradient-to-r from-primary to-purple-600 text-primary-foreground rounded-full w-8 h-8 flex items-center justify-center mr-3 flex-shrink-0 font-bold shadow-sm">
                  2
                </div>
                <p className="text-foreground">Hands-on technical workshops</p>
              </div>
              <div className="flex items-start">
                <div className="bg-gradient-to-r from-primary to-purple-600 text-primary-foreground rounded-full w-8 h-8 flex items-center justify-center mr-3 flex-shrink-0 font-bold shadow-sm">
                  3
                </div>
                <p className="text-foreground">Networking sessions with professionals</p>
              </div>
              <div className="flex items-start">
                <div className="bg-gradient-to-r from-primary to-purple-600 text-primary-foreground rounded-full w-8 h-8 flex items-center justify-center mr-3 flex-shrink-0 font-bold shadow-sm">
                  4
                </div>
                <p className="text-foreground">Innovation showcase and demos</p>
              </div>
            </div>
          </div>
        </div>
        <div className="bg-white/80 backdrop-blur-sm p-4 text-center border-t border-white/30">
          <p className="text-muted-foreground text-sm">
            Organized by Tech Community Foundation • #TechInnovate2023 • www.techinnovate-conference.com
          </p>
        </div>
      </div>
    </div>
 </body>
</html>
