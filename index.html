<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Content Creator Blog Manager</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        :root {
            --primary-dark: #0f1419;
            --primary-accent: #ff6b35;
            --secondary-accent: #f7931e;
            --text-primary: #ffffff;
            --text-secondary: #b8bcc4;
            --bg-card: #1a1f2e;
            --bg-hover: #252d3d;
            --border-color: #2d3748;
            --success-color: #10b981;
            --transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, var(--primary-dark) 0%, #1a2332 100%);
            color: var(--text-primary);
            line-height: 1.6;
            min-height: 100vh;
        }

        /* ======================== HEADER & NAVIGATION ======================== */
        header {
            position: sticky;
            top: 0;
            z-index: 1000;
            background: rgba(15, 20, 25, 0.95);
            backdrop-filter: blur(10px);
            border-bottom: 1px solid var(--border-color);
            padding: 0 20px;
            transition: var(--transition);
        }

        .header-container {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
            height: 70px;
        }

        .logo {
            font-size: 28px;
            font-weight: 800;
            background: linear-gradient(135deg, var(--primary-accent), var(--secondary-accent));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            letter-spacing: -1px;
            cursor: pointer;
            transition: var(--transition);
        }

        .logo:hover {
            transform: scale(1.05);
        }

        nav {
            display: flex;
            gap: 40px;
            align-items: center;
        }

        nav a {
            color: var(--text-secondary);
            text-decoration: none;
            font-size: 14px;
            font-weight: 500;
            text-transform: uppercase;
            letter-spacing: 0.5px;
            position: relative;
            transition: var(--transition);
        }

        nav a:hover {
            color: var(--primary-accent);
        }

        nav a::after {
            content: '';
            position: absolute;
            bottom: -5px;
            left: 0;
            width: 0;
            height: 2px;
            background: var(--primary-accent);
            transition: var(--transition);
        }

        nav a:hover::after {
            width: 100%;
        }

        nav a.active {
            color: var(--primary-accent);
        }

        nav a.active::after {
            width: 100%;
        }

        .nav-toggle {
            display: none;
            flex-direction: column;
            cursor: pointer;
            gap: 5px;
        }

        .nav-toggle span {
            width: 25px;
            height: 3px;
            background: var(--primary-accent);
            border-radius: 2px;
            transition: var(--transition);
        }

        /* ======================== HERO SECTION ======================== */
        .hero {
            max-width: 1200px;
            margin: 0 auto;
            padding: 60px 20px;
            text-align: center;
        }

        .hero h1 {
            font-size: 56px;
            font-weight: 900;
            margin-bottom: 20px;
            letter-spacing: -2px;
            line-height: 1.1;
        }

        .hero .gradient-text {
            background: linear-gradient(135deg, var(--primary-accent), var(--secondary-accent));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        .hero p {
            font-size: 18px;
            color: var(--text-secondary);
            max-width: 600px;
            margin: 0 auto 40px;
            line-height: 1.8;
        }

        .search-container {
            max-width: 600px;
            margin: 0 auto;
            display: flex;
            gap: 10px;
        }

        .search-input {
            flex: 1;
            padding: 14px 20px;
            background: var(--bg-card);
            border: 1px solid var(--border-color);
            border-radius: 8px;
            color: var(--text-primary);
            font-size: 14px;
            transition: var(--transition);
        }

        .search-input:focus {
            outline: none;
            border-color: var(--primary-accent);
            box-shadow: 0 0 0 3px rgba(255, 107, 53, 0.1);
            background: var(--bg-hover);
        }

        .search-input::placeholder {
            color: var(--text-secondary);
        }

        /* ======================== FILTERS & CONTROLS ======================== */
        .controls-section {
            max-width: 1200px;
            margin: 40px auto 0;
            padding: 0 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 20px;
        }

        .filter-group {
            display: flex;
            gap: 10px;
            flex-wrap: wrap;
            align-items: center;
        }

        .filter-label {
            font-size: 12px;
            text-transform: uppercase;
            color: var(--text-secondary);
            font-weight: 600;
            letter-spacing: 1px;
        }

        .filter-tag {
            padding: 8px 16px;
            background: var(--bg-card);
            border: 1px solid var(--border-color);
            color: var(--text-secondary);
            border-radius: 6px;
            cursor: pointer;
            font-size: 13px;
            transition: var(--transition);
            font-weight: 500;
        }

        .filter-tag:hover {
            border-color: var(--primary-accent);
            color: var(--primary-accent);
            background: rgba(255, 107, 53, 0.1);
        }

        .filter-tag.active {
            background: var(--primary-accent);
            border-color: var(--primary-accent);
            color: var(--primary-dark);
        }

        .sort-select {
            padding: 8px 14px;
            background: var(--bg-card);
            border: 1px solid var(--border-color);
            color: var(--text-primary);
            border-radius: 6px;
            font-size: 13px;
            cursor: pointer;
            transition: var(--transition);
            font-weight: 500;
        }

        .sort-select:hover {
            border-color: var(--primary-accent);
        }

        .sort-select:focus {
            outline: none;
            border-color: var(--primary-accent);
            box-shadow: 0 0 0 3px rgba(255, 107, 53, 0.1);
        }

        .sort-select option {
            background: var(--bg-card);
            color: var(--text-primary);
        }

        /* ======================== BLOG GRID ======================== */
        .blog-section {
            max-width: 1200px;
            margin: 60px auto 0;
            padding: 0 20px 80px;
        }

        .section-title {
            font-size: 32px;
            font-weight: 800;
            margin-bottom: 40px;
            display: flex;
            align-items: center;
            gap: 15px;
        }

        .section-title::before {
            content: '';
            display: inline-block;
            width: 4px;
            height: 32px;
            background: linear-gradient(180deg, var(--primary-accent), var(--secondary-accent));
            border-radius: 2px;
        }

        .blog-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(340px, 1fr));
            gap: 30px;
            margin-bottom: 60px;
        }

        .blog-card {
            background: var(--bg-card);
            border: 1px solid var(--border-color);
            border-radius: 12px;
            overflow: hidden;
            transition: var(--transition);
            cursor: pointer;
            display: flex;
            flex-direction: column;
            height: 100%;
            position: relative;
        }

        .blog-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 3px;
            background: linear-gradient(90deg, var(--primary-accent), var(--secondary-accent));
            opacity: 0;
            transition: var(--transition);
        }

        .blog-card:hover {
            border-color: var(--primary-accent);
            background: var(--bg-hover);
            transform: translateY(-8px);
            box-shadow: 0 20px 40px rgba(255, 107, 53, 0.15);
        }

        .blog-card:hover::before {
            opacity: 1;
        }

        .blog-image {
            width: 100%;
            height: 200px;
            background: linear-gradient(135deg, rgba(255, 107, 53, 0.2), rgba(247, 147, 30, 0.2));
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 48px;
            overflow: hidden;
            position: relative;
        }

        .blog-image.has-image {
            background-size: cover;
            background-position: center;
        }

        .blog-content {
            padding: 24px;
            display: flex;
            flex-direction: column;
            flex: 1;
        }

        .blog-category {
            display: inline-block;
            padding: 6px 12px;
            background: rgba(255, 107, 53, 0.15);
            color: var(--primary-accent);
            border-radius: 4px;
            font-size: 11px;
            font-weight: 700;
            text-transform: uppercase;
            letter-spacing: 0.5px;
            margin-bottom: 12px;
            width: fit-content;
        }

        .blog-title {
            font-size: 20px;
            font-weight: 700;
            margin-bottom: 12px;
            line-height: 1.3;
            color: var(--text-primary);
            transition: var(--transition);
        }

        .blog-card:hover .blog-title {
            color: var(--primary-accent);
        }

        .blog-excerpt {
            font-size: 14px;
            color: var(--text-secondary);
            margin-bottom: auto;
            line-height: 1.6;
        }

        .blog-footer {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-top: 20px;
            padding-top: 16px;
            border-top: 1px solid var(--border-color);
        }

        .blog-meta {
            display: flex;
            gap: 12px;
            font-size: 12px;
            color: var(--text-secondary);
        }

        .blog-meta-item {
            display: flex;
            align-items: center;
            gap: 6px;
        }

        .read-more {
            padding: 8px 16px;
            background: linear-gradient(135deg, var(--primary-accent), var(--secondary-accent));
            color: var(--primary-dark);
            border: none;
            border-radius: 6px;
            font-size: 12px;
            font-weight: 600;
            cursor: pointer;
            transition: var(--transition);
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }

        .read-more:hover {
            transform: scale(1.05);
            box-shadow: 0 8px 16px rgba(255, 107, 53, 0.3);
        }

        /* ======================== MODAL ======================== */
        .modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: rgba(15, 20, 25, 0.8);
            backdrop-filter: blur(5px);
            z-index: 2000;
            animation: fadeIn 0.3s ease-out;
        }

        .modal.active {
            display: flex;
            align-items: center;
            justify-content: center;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

        .modal-content {
            background: var(--bg-card);
            border: 1px solid var(--border-color);
            border-radius: 16px;
            padding: 40px;
            max-width: 700px;
            max-height: 90vh;
            overflow-y: auto;
            animation: slideUp 0.3s ease-out;
            position: relative;
        }

        @keyframes slideUp {
            from {
                transform: translateY(30px);
                opacity: 0;
            }
            to {
                transform: translateY(0);
                opacity: 1;
            }
        }

        .modal-close {
            position: absolute;
            top: 20px;
            right: 20px;
            width: 32px;
            height: 32px;
            background: var(--bg-hover);
            border: 1px solid var(--border-color);
            border-radius: 50%;
            cursor: pointer;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 20px;
            color: var(--text-secondary);
            transition: var(--transition);
        }

        .modal-close:hover {
            background: var(--primary-accent);
            color: var(--primary-dark);
            border-color: var(--primary-accent);
        }

        .modal-header {
            margin-bottom: 30px;
        }

        .modal-title {
            font-size: 32px;
            font-weight: 800;
            margin-bottom: 12px;
            line-height: 1.2;
        }

        .modal-meta {
            display: flex;
            gap: 20px;
            font-size: 13px;
            color: var(--text-secondary);
            flex-wrap: wrap;
        }

        .modal-body {
            font-size: 15px;
            line-height: 1.8;
            color: var(--text-secondary);
            margin-bottom: 30px;
        }

        .modal-body p {
            margin-bottom: 16px;
        }

        .modal-body strong {
            color: var(--text-primary);
        }

        .modal-tags {
            display: flex;
            gap: 10px;
            flex-wrap: wrap;
        }

        .modal-tag {
            padding: 6px 14px;
            background: rgba(255, 107, 53, 0.15);
            color: var(--primary-accent);
            border-radius: 4px;
            font-size: 12px;
            font-weight: 600;
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }

        /* ======================== EMPTY STATE ======================== */
        .empty-state {
            text-align: center;
            padding: 60px 20px;
            color: var(--text-secondary);
        }

        .empty-state-icon {
            font-size: 64px;
            margin-bottom: 20px;
            opacity: 0.5;
        }

        .empty-state h3 {
            font-size: 24px;
            margin-bottom: 10px;
            color: var(--text-primary);
        }

        /* ======================== LOADING STATE ======================== */
        .loading-spinner {
            display: inline-block;
            width: 40px;
            height: 40px;
            border: 3px solid var(--border-color);
            border-top-color: var(--primary-accent);
            border-radius: 50%;
            animation: spin 0.8s linear infinite;
        }

        @keyframes spin {
            to {
                transform: rotate(360deg);
            }
        }

        .loading-container {
            display: flex;
            justify-content: center;
            padding: 60px 20px;
        }

        /* ======================== RESPONSIVE ======================== */
        @media (max-width: 768px) {
            .header-container {
                height: 60px;
            }

            .logo {
                font-size: 22px;
            }

            nav {
                position: fixed;
                top: 60px;
                left: 0;
                right: 0;
                flex-direction: column;
                gap: 0;
                background: var(--bg-card);
                border-bottom: 1px solid var(--border-color);
                max-height: 0;
                overflow: hidden;
                transition: var(--transition);
                z-index: 999;
            }

            nav.active {
                max-height: 400px;
            }

            nav a {
                padding: 16px 20px;
                border-bottom: 1px solid var(--border-color);
                width: 100%;
            }

            .nav-toggle {
                display: flex;
            }

            .hero {
                padding: 40px 20px;
            }

            .hero h1 {
                font-size: 36px;
            }

            .hero p {
                font-size: 16px;
            }

            .search-container {
                flex-direction: column;
            }

            .controls-section {
                flex-direction: column;
                align-items: stretch;
            }

            .filter-group {
                width: 100%;
            }

            .blog-grid {
                grid-template-columns: 1fr;
            }

            .section-title {
                font-size: 24px;
            }

            .modal-content {
                padding: 24px;
                margin: 20px;
            }

            .modal-title {
                font-size: 24px;
            }
        }

        @media (max-width: 480px) {
            .hero h1 {
                font-size: 28px;
            }

            .blog-grid {
                gap: 20px;
            }

            .blog-section {
                padding: 0 16px 60px;
            }
        }
    </style>
</head>
<body>
    <!-- ======================== HEADER ======================== -->
    <header>
        <div class="header-container">
            <div class="logo">📝 BlogHub</div>
            <nav id="nav-menu">
                <a href="#home" class="nav-link active" data-page="home">Home</a>
                <a href="#posts" class="nav-link" data-page="posts">All Posts</a>
                <a href="#about" class="nav-link" data-page="about">About</a>
            </nav>
            <div class="nav-toggle" id="nav-toggle">
                <span></span>
                <span></span>
                <span></span>
            </div>
        </div>
    </header>

    <!-- ======================== HERO SECTION ======================== -->
    <section class="hero" id="hero-section">
        <h1>Welcome to <span class="gradient-text">BlogHub</span></h1>
        <p>Discover stories, insights, and ideas from our community of creators. Explore, learn, and get inspired.</p>
        <div class="search-container">
            <input 
                type="text" 
                class="search-input" 
                id="search-input" 
                placeholder="Search posts by title or keyword..."
            >
        </div>
    </section>

    <!-- ======================== CONTROLS ======================== -->
    <div class="controls-section" id="controls-section" style="display: none;">
        <div class="filter-group">
            <span class="filter-label">Filter by Category:</span>
            <div id="category-filters" class="filter-group"></div>
        </div>
        <select class="sort-select" id="sort-select">
            <option value="recent">Most Recent</option>
            <option value="oldest">Oldest First</option>
            <option value="popular">Most Popular</option>
            <option value="a-z">A - Z</option>
        </select>
    </div>

    <!-- ======================== BLOG SECTION ======================== -->
    <section class="blog-section" id="blog-section">
        <div class="section-title">Recent Posts</div>
        <div id="loading-container" class="loading-container">
            <div class="loading-spinner"></div>
        </div>
        <div id="blog-grid" class="blog-grid"></div>
        <div id="empty-state" class="empty-state" style="display: none;">
            <div class="empty-state-icon">📭</div>
            <h3>No posts found</h3>
            <p>Try adjusting your filters or search query</p>
        </div>
    </section>

    <!-- ======================== MODAL ======================== -->
    <div class="modal" id="modal">
        <div class="modal-content">
            <div class="modal-close" id="modal-close">&times;</div>
            <div class="modal-header">
                <h2 class="modal-title" id="modal-title"></h2>
                <div class="modal-meta" id="modal-meta"></div>
            </div>
            <div class="modal-body" id="modal-body"></div>
            <div class="modal-tags" id="modal-tags"></div>
        </div>
    </div>

    <script>
        // ======================== STATE MANAGEMENT ========================
        const state = {
            allPosts: [],
            filteredPosts: [],
            currentFilter: 'all',
            searchQuery: '',
            sortBy: 'recent',
            categories: new Set()
        };

        // ======================== DOM ELEMENTS ========================
        const elements = {
            navLinks: document.querySelectorAll('.nav-link'),
            navMenu: document.getElementById('nav-menu'),
            navToggle: document.getElementById('nav-toggle'),
            searchInput: document.getElementById('search-input'),
            blogGrid: document.getElementById('blog-grid'),
            modal: document.getElementById('modal'),
            modalClose: document.getElementById('modal-close'),
            loadingContainer: document.getElementById('loading-container'),
            emptyState: document.getElementById('empty-state'),
            categoryFilters: document.getElementById('category-filters'),
            sortSelect: document.getElementById('sort-select'),
            controlsSection: document.getElementById('controls-section')
        };

        // ======================== FETCH BLOGS DATA ========================
        async function fetchBlogs() {
            try {
                // Check if blogs.json exists in the same directory
                const response = await fetch('blogs.json');
                if (!response.ok) {
                    throw new Error('Could not fetch blogs.json');
                }
                state.allPosts = await response.json();
                initializeFilters();
                filterAndDisplayBlogs();
            } catch (error) {
                console.error('Error loading blogs:', error);
                loadSampleData();
            }
        }

        // ======================== SAMPLE DATA (FALLBACK) ========================
        function loadSampleData() {
            state.allPosts = [
                {
                    id: 1,
                    title: "Getting Started with Web Development",
                    excerpt: "Learn the fundamentals of HTML, CSS, and JavaScript to build your first website.",
                    content: "Web development is an exciting field that opens doors to countless opportunities. In this comprehensive guide, we'll explore the three core technologies that power the web: HTML, CSS, and JavaScript.\n\nHTML provides the structure of your webpage, CSS handles the styling and layout, while JavaScript adds interactivity. By mastering these technologies, you'll be able to create engaging web experiences.\n\nStart with HTML basics, move to CSS styling, and then dive into JavaScript programming. Practice regularly and build projects to solidify your learning.",
                    category: "Web Development",
                    author: "Sarah Johnson",
                    date: "2024-01-15",
                    readTime: 8,
                    views: 1240,
                    tags: ["html", "css", "javascript", "beginner"]
                },
                {
                    id: 2,
                    title: "Advanced React Patterns and Best Practices",
                    excerpt: "Master advanced React concepts including hooks, context, and performance optimization.",
                    content: "React has become the go-to library for building modern web applications. This article explores advanced patterns that will make you a better React developer.\n\nWe'll cover custom hooks, context API for state management, error boundaries, and performance optimization techniques. You'll learn how to write more maintainable and efficient React code.\n\nUnderstanding these patterns will significantly improve your development workflow and code quality.",
                    category: "React",
                    author: "Michael Chen",
                    date: "2024-01-20",
                    readTime: 12,
                    views: 2150,
                    tags: ["react", "javascript", "advanced"]
                },
                {
                    id: 3,
                    title: "The Future of AI and Machine Learning",
                    excerpt: "Exploring the emerging trends and technologies shaping the future of artificial intelligence.",
                    content: "Artificial Intelligence is rapidly transforming how we work and live. From machine learning to deep learning, the field is evolving at an unprecedented pace.\n\nWe examine the latest developments in AI, including transformer models, natural language processing, and computer vision. Understanding these technologies is crucial for developers looking to stay ahead.\n\nThe future belongs to those who can harness the power of AI responsibly and effectively.",
                    category: "AI & Technology",
                    author: "Dr. Elena Rodriguez",
                    date: "2024-01-25",
                    readTime: 15,
                    views: 3420,
                    tags: ["ai", "machine-learning", "technology"]
                },
                {
                    id: 4,
                    title: "Design Principles for User-Centric Applications",
                    excerpt: "Create beautiful and intuitive user interfaces by following established design principles.",
                    content: "Good design is invisible. Users don't notice great design; they only notice poor design. In this guide, we explore the principles that make applications a pleasure to use.\n\nWe discuss visual hierarchy, consistency, feedback, and accessibility. These principles apply whether you're designing a website, mobile app, or desktop application.\n\nBy applying these principles, you can create applications that users love to interact with.",
                    category: "Design",
                    author: "Lisa Wang",
                    date: "2024-02-01",
                    readTime: 10,
                    views: 1890,
                    tags: ["design", "ux", "ui"]
                },
                {
                    id: 5,
                    title: "Mastering CSS Grid and Flexbox",
                    excerpt: "Build responsive layouts with modern CSS layout techniques.",
                    content: "CSS Grid and Flexbox are game-changers for web layout. These powerful tools make it easy to create responsive designs without relying on frameworks or hacks.\n\nWe explore the differences between Grid and Flexbox, when to use each, and how they can work together. You'll learn practical techniques through real-world examples.\n\nMastering these layouts will make you a more efficient and effective web developer.",
                    category: "Web Development",
                    author: "David Kumar",
                    date: "2024-02-05",
                    readTime: 9,
                    views: 2340,
                    tags: ["css", "layout", "responsive"]
                },
                {
                    id: 6,
                    title: "Building Scalable Node.js Applications",
                    excerpt: "Best practices for developing robust and scalable backend services with Node.js.",
                    content: "Node.js has revolutionized backend development. Its event-driven architecture makes it perfect for building scalable applications that handle thousands of concurrent connections.\n\nIn this guide, we cover architecture patterns, database optimization, caching strategies, and monitoring. You'll learn how to build applications that can grow with your user base.\n\nFrom small projects to enterprise-level applications, these practices will serve you well.",
                    category: "Backend",
                    author: "James Wilson",
                    date: "2024-02-10",
                    readTime: 14,
                    views: 2780,
                    tags: ["nodejs", "backend", "scalability"]
                }
            ];
            initializeFilters();
            filterAndDisplayBlogs();
        }

        // ======================== INITIALIZE FILTERS ========================
        function initializeFilters() {
            state.categories = new Set(state.allPosts.map(post => post.category));
            renderCategoryFilters();
        }

        // ======================== RENDER CATEGORY FILTERS ========================
        function renderCategoryFilters() {
            elements.categoryFilters.innerHTML = '';
            
            // Add "All" filter
            const allFilter = document.createElement('button');
            allFilter.className = 'filter-tag active';
            allFilter.textContent = 'All';
            allFilter.onclick = () => {
                document.querySelectorAll('.filter-tag').forEach(tag => tag.classList.remove('active'));
                allFilter.classList.add('active');
                state.currentFilter = 'all';
                filterAndDisplayBlogs();
            };
            elements.categoryFilters.appendChild(allFilter);

            // Add category filters
            state.categories.forEach(category => {
                const filter = document.createElement('button');
                filter.className = 'filter-tag';
                filter.textContent = category;
                filter.onclick = () => {
                    document.querySelectorAll('.filter-tag').forEach(tag => tag.classList.remove('active'));
                    filter.classList.add('active');
                    state.currentFilter = category;
                    filterAndDisplayBlogs();
                };
                elements.categoryFilters.appendChild(filter);
            });
        }

        // ======================== FILTER AND DISPLAY BLOGS ========================
        function filterAndDisplayBlogs() {
            // Filter by category
            let filtered = state.allPosts;
            if (state.currentFilter !== 'all') {
                filtered = filtered.filter(post => post.category === state.currentFilter);
            }

            // Filter by search query
            if (state.searchQuery) {
                const query = state.searchQuery.toLowerCase();
                filtered = filtered.filter(post =>
                    post.title.toLowerCase().includes(query) ||
                    post.excerpt.toLowerCase().includes(query) ||
                    post.tags.some(tag => tag.includes(query))
                );
            }

            // Sort
            filtered = sortPosts(filtered, state.sortBy);

            state.filteredPosts = filtered;
            renderBlogGrid();
        }

        // ======================== SORT POSTS ========================
        function sortPosts(posts, sortBy) {
            const sorted = [...posts];
            switch(sortBy) {
                case 'recent':
                    return sorted.sort((a, b) => new Date(b.date) - new Date(a.date));
                case 'oldest':
                    return sorted.sort((a, b) => new Date(a.date) - new Date(b.date));
                case 'popular':
                    return sorted.sort((a, b) => b.views - a.views);
                case 'a-z':
                    return sorted.sort((a, b) => a.title.localeCompare(b.title));
                default:
                    return sorted;
            }
        }

        // ======================== RENDER BLOG GRID ========================
        function renderBlogGrid() {
            const grid = elements.blogGrid;
            grid.innerHTML = '';

            if (state.filteredPosts.length === 0) {
                elements.emptyState.style.display = 'block';
                elements.loadingContainer.style.display = 'none';
                return;
            }

            elements.emptyState.style.display = 'none';
            elements.loadingContainer.style.display = 'none';
            elements.controlsSection.style.display = 'flex';

            state.filteredPosts.forEach(post => {
                const card = createBlogCard(post);
                grid.appendChild(card);
            });
        }

        // ======================== CREATE BLOG CARD ========================
        function createBlogCard(post) {
            const card = document.createElement('div');
            card.className = 'blog-card';
            card.innerHTML = `
                <div class="blog-image" style="background: linear-gradient(135deg, rgba(255, 107, 53, 0.2), rgba(247, 147, 30, 0.2));">
                    <span style="font-size: 48px;">📖</span>
                </div>
                <div class="blog-content">
                    <span class="blog-category">${post.category}</span>
                    <h3 class="blog-title">${escapeHtml(post.title)}</h3>
                    <p class="blog-excerpt">${escapeHtml(post.excerpt)}</p>
                    <div class="blog-footer">
                        <div class="blog-meta">
                            <div class="blog-meta-item">📅 ${formatDate(post.date)}</div>
                            <div class="blog-meta-item">⏱️ ${post.readTime}m</div>
                        </div>
                        <button class="read-more" onclick="openModal(${post.id})">Read More</button>
                    </div>
                </div>
            `;
            return card;
        }

        // ======================== OPEN MODAL ========================
        function openModal(postId) {
            const post = state.allPosts.find(p => p.id === postId);
            if (!post) return;

            document.getElementById('modal-title').textContent = post.title;
            document.getElementById('modal-meta').innerHTML = `
                <div class="blog-meta-item">👤 ${post.author}</div>
                <div class="blog-meta-item">📅 ${formatDate(post.date)}</div>
                <div class="blog-meta-item">⏱️ ${post.readTime} min read</div>
                <div class="blog-meta-item">👁️ ${post.views} views</div>
            `;
            document.getElementById('modal-body').innerHTML = post.content.split('\n').map(p => p.trim()).filter(p => p).map(p => `<p>${escapeHtml(p)}</p>`).join('');
            
            const tagsContainer = document.getElementById('modal-tags');
            tagsContainer.innerHTML = '';
            post.tags.forEach(tag => {
                const tagEl = document.createElement('span');
                tagEl.className = 'modal-tag';
                tagEl.textContent = tag;
                tagsContainer.appendChild(tagEl);
            });

            elements.modal.classList.add('active');
            document.body.style.overflow = 'hidden';
        }

        // ======================== CLOSE MODAL ========================
        function closeModal() {
            elements.modal.classList.remove('active');
            document.body.style.overflow = 'auto';
        }

        // ======================== FORMAT DATE ========================
        function formatDate(dateStr) {
            const date = new Date(dateStr);
            return date.toLocaleDateString('en-US', { year: 'numeric', month: 'short', day: 'numeric' });
        }

        // ======================== ESCAPE HTML ========================
        function escapeHtml(text) {
            const div = document.createElement('div');
            div.textContent = text;
            return div.innerHTML;
        }

        // ======================== EVENT LISTENERS ========================
        
        // Search functionality
        elements.searchInput.addEventListener('input', (e) => {
            state.searchQuery = e.target.value;
            filterAndDisplayBlogs();
        });

        // Sort functionality
        elements.sortSelect.addEventListener('change', (e) => {
            state.sortBy = e.target.value;
            filterAndDisplayBlogs();
        });

        // Modal close
        elements.modalClose.addEventListener('click', closeModal);
        elements.modal.addEventListener('click', (e) => {
            if (e.target === elements.modal) closeModal();
        });

        // Navigation toggle (mobile)
        elements.navToggle.addEventListener('click', () => {
            elements.navMenu.classList.toggle('active');
        });

        // Navigation links
        elements.navLinks.forEach(link => {
            link.addEventListener('click', () => {
                elements.navLinks.forEach(l => l.classList.remove('active'));
                link.classList.add('active');
                elements.navMenu.classList.remove('active');
            });
        });

        // ======================== INITIALIZE APP ========================
        document.addEventListener('DOMContentLoaded', () => {
            fetchBlogs();
        });
    </script>
</body>
</html>
